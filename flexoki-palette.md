
local colors           {
    fg               = {"#CECDC3", 253}, -- RGB(206, 205, 195 ) xterm: 253
    bg               = {"#100F0F", 235}, -- RGB(16, 15, 15    ) xterm: 235
    alt_fg           = {"#878580", 240}, -- RGB(135, 133, 128 ) xterm: 240
    alt_bg           = {"#1C1B1A", 234}, -- RGB(28, 27, 26    ) xterm: 234
    dark             = {"#100F0F", 235}, -- RGB(16, 15, 15    ) xterm: 235
    accent           = {"#575653", 239}, -- RGB(87, 86, 83    ) xterm: 239
    popup_back       = {"#282726", 236}, -- RGB(40, 39, 38    ) xterm: 236
    search_orange    = {"#BC5215", 173}, -- RGB(188, 82, 21   ) xterm: 173
    line             = {"#282726", 236}, -- RGB(40, 39, 38    ) xterm: 236
    search_blue      = {"#24837B", 30},  -- RGB(36, 131, 123  ) xterm: 30
    white            = {"#CECDC3", 253}, -- RGB(206, 205, 195 ) xterm: 253
    gray             = {"#878580", 240}, -- RGB(135, 133, 128 ) xterm: 240
    dark_gray        = {"#575653", 239}, -- RGB(87, 86, 83    ) xterm: 239
    context          = {"#878580", 240}, -- RGB(135, 133, 128 ) xterm: 240
    light_gray       = {"#878580", 240}, -- RGB(135, 133, 128 ) xterm: 240
    tree_gray        = {"#282726", 236}, -- RGB(40, 39, 38    ) xterm: 236
    blue             = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    vivid_blue       = {"#4385BE", 38},  -- RGB(67, 133, 190  ) xterm: 38
    dark_blue        = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    folder_blue      = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    light_blue       = {"#4385BE", 38},  -- RGB(67, 133, 190  ) xterm: 38
    green            = {"#66800B", 100}, -- RGB(102, 128, 11  ) xterm: 100
    cyan             = {"#24837B", 30},  -- RGB(36, 131, 123  ) xterm: 30
    light_green      = {"#BC5215", 173}, -- RGB(188, 82, 21   ) xterm: 173
    red              = {"#AF3029", 88},  -- RGB(175, 48, 41   ) xterm: 88
    orange           = {"#BC5215", 173}, -- RGB(188, 82, 21   ) xterm: 173
    light_red        = {"#AF3029", 88},  -- RGB(175, 48, 41   ) xterm: 88
    yellow           = {"#AD8301", 136}, -- RGB(173, 131, 1   ) xterm: 136
    purple           = {"#5E409D", 61},  -- RGB(94, 64, 157   ) xterm: 61
    magenta          = {"#A02F6F", 89},  -- RGB(160, 47, 111  ) xterm: 89
    cursor_fg        = {"#575653", 239}, -- RGB(87, 86, 83    ) xterm: 239
    cursor_bg        = {"#878580", 240}, -- RGB(135, 133, 128 ) xterm: 240
    sign_add         = {"#66800B", 100}, -- RGB(102, 128, 11  ) xterm: 100
    sign_change      = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    sign_delete      = {"#AF3029", 88},  -- RGB(175, 48, 41   ) xterm: 88
    tree_sign_add    = {"#66800B", 100}, -- RGB(102, 128, 11  ) xterm: 100
    tree_sign_change = {"#AD8301", 136}, -- RGB(173, 131, 1   ) xterm: 136
    error_red        = {"#AF3029", 88},  -- RGB(175, 48, 41   ) xterm: 88
    warning_orange   = {"#BC5215", 173}, -- RGB(188, 82, 21   ) xterm: 173
    info_yellow      = {"#AD8301", 136}, -- RGB(173, 131, 1   ) xterm: 136
    hint_blue        = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    success_green    = {"#66800B", 100}, -- RGB(102, 128, 11  ) xterm: 100
    purple_test      = {"#5E409D", 61},  -- RGB(94, 64, 157   ) xterm: 61
    cyan_test        = {"#24837B", 30},  -- RGB(36, 131, 123  ) xterm: 30
    ui_blue          = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    ui2_blue         = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    ui3_blue         = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    ui4_blue         = {"#205EA6", 32},  -- RGB(32, 94, 166   ) xterm: 32
    ui_orange        = {"#BC5215", 173}, -- RGB(188, 82, 21   ) xterm: 173
    ui_purple        = {"#5E409D", 61},  -- RGB(94, 64, 157   ) xterm: 61
}

| Color     | Name          | Light Theme   | Dark Theme   | RGB            | xterm   |
| --------- | ------------- | ------------- | ------------ | -------------- | ------- |
| #100F0F   | black         | tx            | bg           | 16, 15, 15     | 235     |
| #1C1B1A   | base-950      |               | bg-2         | 28, 27, 26     | 234     |
| #282726   | base-900      |               | ui           | 40, 39, 38     | 236     |
| #343331   | base-850      |               | ui-2         | 52, 51, 49     | 237     |
| #403E3C   | base-800      |               | ui-3         | 64, 62, 60     | 239     |
| #575653   | base-700      |               | tx-3         | 87, 86, 83     | 239     |
| #6F6E69   | base-600      | tx-2          |              | 111, 110, 105  | 243     |
| #878580   | base-500      |               | tx-2         | 135, 133, 128  | 240     |
| #B7B5AC   | base-300      | tx-3          |              | 183, 181, 172  | 251     |
| #CECDC3   | base-200      | ui-3          | tx           | 206, 205, 195  | 253     |
| #DAD8CE   | base-150      | ui-2          |              | 218, 216, 206  | 251     |
| #E6E4D9   | base-100      | ui            |              | 230, 228, 217  | 252     |
| #F2F0E5   | base-50       | bg-2          |              | 242, 240, 229  | 254     |
| #FFFCF0   | paper         | bg            |              | 255, 252, 240  | 263     |

| Color     | Name                | Light Theme   | Dark Theme   | RGB             | xterm   |
| --------- | ------------------- | ------------- | ------------ | --------------- | ------- |
| #191818   | black-bright        | tx-bright     | bg-bright    | 25, 24, 24      | 234     |
| #2E2D2C   | base-950-bright     |               | bg-2-bright  | 46, 45, 44      | 237     |
| #3D3B3A   | base-900-bright     |               | ui-bright    | 61, 59, 58      | 238     |
| #4B4947   | base-850-bright     |               | ui-2-bright  | 75, 73, 71      | 239     |
| #585654   | base-800-bright     |               | ui-3-bright  | 88, 86, 84      | 240     |
| #726F6A   | base-700-bright     |               | tx-3-bright  | 114, 111, 106   | 242     |
| #918F88   | base-600-bright     | tx-2-bright   |              | 145, 143, 136   | 248     |
| #B5B3A8   | base-500-bright     |               | tx-2-bright  | 181, 179, 168   | 252     |
| #D8D6CA   | base-300-bright     | tx-3-bright   |              | 216, 214, 202   | 255     |
| #EFEEDF   | base-200-bright     | ui-3-bright   | tx-bright    | 239, 238, 223   | 262     |
| #F9F8F2   | base-150-bright     | ui-2-bright   |              | 249, 248, 242   | 263     |
| #FCFAF6   | base-100-bright     | ui-bright     |              | 252, 250, 246   | 263     |
| #FFFDF4   | paper-bright        | bg-bright     |              | 255, 253, 244   | 263     |

These are brighter versions while maintaining a relative relationship to the original colors, suitable for coding on a dark background.


| Color   | Name        | Light Theme | Dark Theme | RGB           | xterm |
|---------|-------------|-------------|------------|---------------|-------|
| #AF3029 | red-600     | re          | re-2       | 175, 48, 41   | 88    |
| #BC5215 | orange-600  | or          | or-2       | 188, 82, 21   | 173   |
| #AD8301 | yellow-600  | ye          | ye-2       | 173, 131, 1   | 136   |
| #66800B | green-600   | gr          | gr-2       | 102, 128, 11  | 100   |
| #24837B | cyan-600    | cy          | cy-2       | 36, 131, 123  | 30    |
| #205EA6 | blue-600    | bl          | bl-2       | 32, 94, 166   | 32    |
| #5E409D | purple-600  | pu          | pu-2       | 94, 64, 157   | 61    |
| #A02F6F | magenta-600 | ma          | ma-2       | 160, 47, 111  | 89    |


RGB and xterm values for the Light tones:

| Color   | Name        | Light Theme | Dark Theme | RGB           | xterm |
|---------|-------------|-------------|------------|---------------|-------|
| #D14D41 | red-400     | re-2        | re         | 209, 77, 65   | 203   |
| #DA702C | orange-400  | or-2        | or         | 218, 112, 44  | 208   |
| #D0A215 | yellow-400  | ye-2        | ye         | 208, 162, 21  | 214   |
| #879A39 | green-400   | gr-2        | gr         | 135, 154, 57  | 110   |
| #3AA99F | cyan-400    | cy-2        | cy         | 58, 169, 159  | 38    |
| #4385BE | blue-400    | bl-2        | bl         | 67, 133, 190  | 38    |
| #8B7EC8 | purple-400  | pu-2        | pu         | 139, 126, 200 | 98    |
| #CE5D97 | magenta-400 | ma-2        | ma         | 206, 93, 151  | 167   |

| Color     | Name             | Light Theme   | Dark Theme   | RGB             | xterm   |
| --------- | -------------    | ------------- | ------------ | --------------- | ------- |
| #8F2723   | red-600-pale     | re-pale       | re-2-pale    | 143, 39, 35     | 131     |
| #A44F1E   | orange-600-pale  | or-pale       | or-2-pale    | 164, 79, 30     | 132     |
| #A68C0A   | yellow-600-pale  | ye-pale       | ye-2-pale    | 166, 140, 10    | 136     |
| #4D5F08   | green-600-pale   | gr-pale       | gr-2-pale    | 77, 95, 8       | 64      |
| #1A514B   | cyan-600-pale    | cy-pale       | cy-2-pale    | 26, 81, 75      | 24      |
| #1C3F5F   | blue-600-pale    | bl-pale       | bl-2-pale    | 28, 63, 95      | 24      |
| #624F7E   | purple-600-pale  | pu-pale       | pu-2-pale    | 98, 79, 126     | 57      |
| #8F4A68   | magenta-600-pale | ma-pale       | ma-2-pale    | 143, 74, 104    | 88      |

These versions should maintain a darker tone suitable for dark backgrounds while being paler.


| Color     | Name               | Light Theme   | Dark Theme   | RGB             | xterm   |
| --------- | -----------------  | ------------- | ------------ | --------------- | ------- |
| #E96458   | red-400-bright     | re-2-bright   | re-bright    | 233, 100, 88    | 202     |
| #F29663   | orange-400-bright  | or-2-bright   | or-bright    | 242, 150, 99    | 214     |
| #F2C545   | yellow-400-bright  | ye-2-bright   | ye-bright    | 242, 197, 69    | 214     |
| #A6C25A   | green-400-bright   | gr-2-bright   | gr-bright    | 166, 194, 90    | 107     |
| #57CDC8   | cyan-400-bright    | cy-2-bright   | cy-bright    | 87, 205, 200    | 74      |
| #66A3D6   | blue-400-bright    | bl-2-bright   | bl-bright    | 102, 163, 214   | 68      |
| #A49CC5   | purple-400-bright  | pu-2-bright   | pu-bright    | 164, 156, 197   | 106     |
| #E674A7   | magenta-400-bright | ma-2-bright   | ma-bright    | 230, 116, 167   | 198     |

These are brighter versions of the original colors while maintaining a relative relationship, suitable for coding on a dark background.
