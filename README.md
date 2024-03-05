# My personal colorscheme's

Fork of https://github.com/nvimdev/nightsky.vim

Commented out highlights:
```vim
"-@plugin
exe 'hi GitGutterAdd' . s:fg_teal
exe 'hi GitGutterChange' . s:fg_blue
exe 'hi GitGutterDelete' . s:fg_red
exe 'hi GitGutterChangeDelete' . s:fg_red
"dashboard
exe 'hi DashboardHeader' . s:fg_green
hi! link DashboardFooter Comment
exe 'hi DashboardProjectTitle' . s:fg_yellow .' gui=bold'
exe 'hi DashboardProjectTitleIcon' . s:fg_purple
exe 'hi DashboardProjectIcon' . s:fg_blue
hi! link  DashboardMruTitle DashboardProjectTitle
hi! link  DashboardMruIcon DashboardProjectTitleIcon
exe 'hi DashboardFiles' . s:fg_fg_alt
hi! link DashboardShortCut Comment
hi! link DashboardShortCutIcon @field
"Telescope
exe 'hi TelescopePromptBorder' .s:bg_bg_alt . s:fg_bg_alt
exe 'hi TelescopePromptNormal' .s:bg_bg_alt . s:fg_orange
exe 'hi TelescopeResultsBorder' .s:bg_bg_alt . s:fg_bg_alt
exe 'hi TelescopePreviewBorder' .s:bg_bg_alt . s:fg_bg_alt
exe 'hi TelescopeResultsNormal' . s:fg_fg
exe 'hi TelescopeSelectionCaret' . s:fg_yellow
exe 'hi TelescopeMatching' . s:fg_yellow
"CursorWord
exe 'hi CursorWord' .s:bg_bg_alt
exe 'hi IndentLine' .s:fg_bg_alt
"Lspsaga
exe 'hi SagaVariable' . s:fg_green
"Rapid
exe 'hi RapidFinished' .s:fg_red . ' gui=bold'
exe 'hi RapidTake' .s:fg_purple . ' gui=bold'
exe 'hi RapidDate' .s:fg_purple . ' gui=bold'
exe 'hi RapidFile' . s:fg_blue . ' gui=bold'
exe 'hi RapidTargetPos' . s:fg_teal . ' gui=bold'
"lsp relate
exe 'hi LspSignatureActiveParameter' . s:fg_yellow . ' gui=underline'
"netrw
hi! link netrwTreeBar Comment
```
