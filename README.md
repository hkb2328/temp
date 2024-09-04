//set theme colors

PrimaryColor_Text = If(varAppColorMode = "Dark", "RGBA(9,15,37,1)", "RGBA(255,255,255,1)"); AccentColor = If (varAppColorMode = "Dark", RGBA(254,189,47,1), RGBA(254,189,47,1));

TertiaryColor If(varAppColorMode = "Dark", RGBA(16,25,50,1), RGBA(244,244,244,1)); TertiaryColor_Text = If(varAppColorMode = "Dark", "RGBA(16,25,50,1)", "RGBA(244,244,244,1)");

PrimaryColor If (varAppColorMode = "Dark", RGBA(9,15,37,1), RGBA(255,255,255,1)); AccentColor_Text = If(varAppColorMode = "Dark", "RGBA(254,189,47,1)", "RGBA(254,189,47,1)"); HighlightColor_Text = If(varAppColorMode = "Dark", "RGBA(23,33,69,1)", "RGBA(215,219,230,1)");

Primary TextColor = If(varAppColorMode = "Dark", RGBA(247, 247, 247,1), RGBA(37,52,100,1)); Primary TextColor_Text = If (varAppColorMode = "Dark", "RGBA(247, 247, 247,1)", "RGBA(37,52,100,1)");

Secondary TextColor = If(varAppColorMode = "Dark", RGBA(115,131,176,1), RGBA(115,131,176,1));

Secondary TextColor_Text = If (varAppColorMode = "Dark", "RGBA(115,131,176,1)", "RGBA(115,131,176,1)");

AccentTextColor = If(varAppColorMode = "Dark", RGBA(22,25,39,1), RGBA(22,25,39,1));

AccentTextColor_Text = If(varAppColorMode = "Dark", "RGBA(22,25,39,1)", "RGBA(22,25,39,1)");

HighlightColor = If (varAppColorMode = "Dark", RGBA(23,33,69,1), RGBA(215,219,230,1));

varHoverFill If (varAppColorMode = "Dark", RGBA(255, 255, 255,0.1), RGBA(0,0,0,0.1)); If (varAppColorMode = "Dark", RGBA(255, 255, 255,0.2), RGBA(0,0,0,0.2));

varPressedFill

// set Icons
