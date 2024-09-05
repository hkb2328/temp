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
=======================================================================================================================
Table(

MenuIcon: "<svg xmlns='http://www.w3.org/2000/svg" width='16' height='16' fill='currentColor' class='bi bi-bucket' viewBox="0 0 16 15'> <path d="M2.522 5H28.5.5 0 0 0.494.57411.372 9.14941.5 1.5 0 0 0 4.36 16h7.278a1.5 1.5 0 0 0 1.483-1.27711.373-9.1494.5.5 0 0 0 14 Sh-.52245.5 5.5 0 0 0 2.522 5zm1.005 0a4.5 4.5 0 0 1 8.945 0H3.527zm9.892 1-1.286 8.5748.5.5 8 8 1-494.426H4.368.5.5 0 0 1-494-426L2.58 6h10.838z'/>

</svg>",

MenuID: 1,

MenuName: "Products",

PageNavigation: App.ActiveScreen

MenuIcon: "<svg xmlns='http://www.w3.org/2000/svg" width='16' height='16' fill='currentColor' class='bi bi-bucket' viewBox="0 0 16 16'> <path d="M2.522 5H2a.5.5 0 0 0.494.57411.372 9.14941.5 1.5 0 0 0 4.36 16h7.278a1.5 1.5 000 1.483-1.27711.373-9.1494.5.5 0 0 0 14 5h-52245.5 5.5 0 0 0 2.522 Szm1.005 8a4.5 4.5 0 0 1 8.945 0H3.527zm9.892 1-1.286 8.574a.5.5 8 8 1.494.426H4.368.5.5 8 0 1-494-426L2.58 6h10.8382'/>

</svg>",

MenuID: 2,

MenuName: "Appointments",

PageNavigation: App.ActiveScreen

}

MenuIcon: "<svg xmlns='http://www.w3.org/2000/svg" width='16' height="16" fill='currentColor' class='bi bi-bucket' viewBox='0 8 16 16'> <path d="M2.522 5H23.5.5 0 0 0.494.57411.372 9.14941.5 1.5 0 0 0 4.36 16h7.278a1.5 1.5 0 0 0 1.483-1.27711.373-9.1494.5.5 e e e 14 5h--52245.5 5.5 0 0 0 2.522 5zm1.005 0a4.5 4.5 0 0 1 8.945 0H3.527zm9.892 1-1.286 8.5748.5.5 0 8 1.494.426H4.362.5.5 8 0 1-494-426L2.58 6h10.8382'/>
