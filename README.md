Setting: Intel AMT, Variable: 0x1E2[1] {05 09 E2 01 01 2B 04 2C 04}
	Option: Disabled, Value: 0x0 {09 09 04 00 00 00 10 00 00}
	Option: Enabled, Value: 0x1 {09 09 03 00 01 00 13 00 00}
End of Options {10 02}

---------------------------------------------------------------------------------------------------------------------------------------------------------

Variable Store Select: 0x5 {25 04 05 00}
Variable 0x10[1] equals 0x0 {12 07 10 00 01 00 00}
	Variable Store Select: 0x0 {25 04 00 00}
	Setting: Intel(R) SpeedStep(tm), Variable: 0x23[1] {05 09 23 00 01 E1 00 E2 00}
		Option: Disabled, Value: 0x0 {09 09 04 00 00 00 10 00 00}
		Option: Enabled, Value: 0x1 {09 09 03 00 01 00 13 00 00}
	End of Options {10 02}
End If {18 02}
Suppress If: {0A 03 00}
Variable 0x23[1] equals 0x0 {12 07 23 00 01 00 00}
	Setting: Boot performance mode, Variable: 0x24[1] {05 09 24 00 01 F4 00 F5 00}
		Option: Max Performance, Value: 0x0 {09 09 F6 00 00 00 03 00 00}
		Option: Max Battery, Value: 0x1 {09 09 F7 00 01 00 00 00 00}
	End of Options {10 02}
End If {18 02}
Suppress If: {0A 03 00}
Variable 0x23[1] equals 0x0 {12 07 23 00 01 00 00}
	Grayout If: {19 03 00}
	Variable Store Select: 0x5 {25 04 05 00}
	Variable 0x1[1] equals 0x0 {12 07 01 00 01 00 00}
		Variable Store Select: 0x0 {25 04 00 00}
		Setting: Turbo Mode, Variable: 0x2B[1] {05 09 2B 00 01 FC 00 FD 00}
			Option: Disabled, Value: 0x0 {09 09 04 00 00 00 10 00 00}
			Option: Enabled, Value: 0x1 {09 09 03 00 01 00 13 00 00}
		End of Options {10 02}
	End If0x48907 						End If {18 02}

---------------------------------------------------------------------------------------------------------------------------------------------------------

Setting: Internal Graphics, Variable: 0xBB[1] {05 09 BB 00 01 C4 01 C5 01}
	Option: Auto, Value: 0x2 {09 09 27 01 02 00 13 00 00}
	Option: Disabled, Value: 0x0 {09 09 29 01 00 00 10 00 00}
	Option: Enabled, Value: 0x1 {09 09 28 01 01 00 10 00 00}
End of Options {10 02}
Setting: GTT Size, Variable: 0xA3[1] {05 09 A3 00 01 23 02 24 02}
	Option: 1MB, Value: 0x1 {09 09 25 02 01 00 10 00 00}
	Option: 2MB, Value: 0x2 {09 09 26 02 02 00 13 00 00}
End of Options {10 02}
Setting: Aperture Size, Variable: 0xA4[1] {05 09 A4 00 01 27 02 28 02}
	Option: 128MB, Value: 0x1 {09 09 29 02 01 00 10 00 00}
	Option: 256MB, Value: 0x2 {09 09 2A 02 02 00 13 00 00}
	Option: 512MB, Value: 0x3 {09 09 2B 02 03 00 10 00 00}
End of Options {10 02}
Setting: DVMT Pre-Allocated, Variable: 0xAA[1] {05 09 AA 00 01 87 01 99 01}
	Option: 0M, Value: 0x0 {09 09 88 01 00 00 00 00 00}
	Option: 32M, Value: 0x1 {09 09 89 01 01 00 00 00 00}
	Option: 64M, Value: 0x2 {09 09 8A 01 02 00 13 00 00}
	Option: 96M, Value: 0x3 {09 09 8B 01 03 00 00 00 00}
	Option: 128M, Value: 0x4 {09 09 8C 01 04 00 00 00 00}
	Option: 160M, Value: 0x5 {09 09 8D 01 05 00 00 00 00}
	Option: 192M, Value: 0x6 {09 09 8E 01 06 00 00 00 00}
	Option: 224M, Value: 0x7 {09 09 8F 01 07 00 00 00 00}
	Option: 256M, Value: 0x8 {09 09 90 01 08 00 00 00 00}
	Option: 288M, Value: 0x9 {09 09 91 01 09 00 00 00 00}
	Option: 320M, Value: 0xA {09 09 92 01 0A 00 00 00 00}
	Option: 352M, Value: 0xB {09 09 93 01 0B 00 00 00 00}
	Option: 384M, Value: 0xC {09 09 94 01 0C 00 00 00 00}
	Option: 416M, Value: 0xD {09 09 95 01 0D 00 00 00 00}
	Option: 448M, Value: 0xE {09 09 96 01 0E 00 00 00 00}
	Option: 480M, Value: 0xF {09 09 97 01 0F 00 00 00 00}
	Option: 512M, Value: 0x10 {09 09 98 01 10 00 00 00 00}
End of Options {10 02}
Setting: DVMT Total Gfx Mem, Variable: 0xAB[1] {05 09 AB 00 01 9A 01 9B 01}
	Option: 128M, Value: 0x1 {09 09 9C 01 01 00 00 00 00}
	Option: 256M, Value: 0x2 {09 09 9D 01 02 00 13 00 00}
	Option: MAX, Value: 0x3 {09 09 9E 01 03 00 00 00 00}
End of Options {10 02}
Setting: Gfx Low Power Mode, Variable: 0xA0[1] {05 09 A0 00 01 4D 02 4E 02}
	Option: Enabled, Value: 0x1 {09 09 28 01 01 00 13 00 00}
	Option: Disabled, Value: 0x0 {09 09 29 01 00 00 00 00 00}
End of Options {10 02}
Setting: HDCP Support, Variable: 0x9D[1] {05 09 9D 00 01 47 02 48 02}
	Option: Enabled, Value: 0x1 {09 09 28 01 01 00 13 00 00}
	Option: Disabled, Value: 0x0 {09 09 29 01 00 00 00 00 00}

---------------------------------------------------------------------------------------------------------------------------------------------------------

Subtitle: PEG Port Configuration {02 04 2C 02}
Subtitle:  {02 04 02 00}
Text: PEG0 {03 0B 2E 02 2F 02 30 02 00 00 00}
Suppress If: {0A 03 00}
Variable Store Select: 0x3 {25 04 03 00}
Variable 0x12[1] equals 0x0 {12 07 12 00 01 00 00}
	Variable Store Select: 0x0 {25 04 00 00}
	Setting: PEG0 LinkWidth Control, Variable: 0xD1[1] {05 09 D1 00 01 1D 02 1E 02}
		Option: Auto, Value: 0x0 {09 09 27 01 00 00 13 00 00}
		Option: Force x1, Value: 0x1 {09 09 1F 02 01 00 10 00 00}
		Option: Force x2, Value: 0x2 {09 09 20 02 02 00 10 00 00}
		Option: Force x4, Value: 0x4 {09 09 21 02 04 00 10 00 00}
		Option: Force x8, Value: 0x8 {09 09 22 02 08 00 10 00 00}
	End of Options {10 02}
End If {18 02}
Setting: PEG0 - Gen X, Variable: 0xCD[1] {05 09 CD 00 01 75 02 76 02}
	Option: Auto, Value: 0x0 {09 09 06 00 00 00 13 00 00}
	Option: Gen1, Value: 0x1 {09 09 7D 02 01 00 00 00 00}
	Option: Gen2, Value: 0x2 {09 09 7E 02 02 00 00 00 00}
End of Options {10 02}
Text: PEG1 {03 0B 31 02 32 02 33 02 00 00 00}
Setting: PEG1 - Gen X, Variable: 0xCE[1] {05 09 CE 00 01 77 02 78 02}
	Option: Auto, Value: 0x0 {09 09 06 00 00 00 13 00 00}
	Option: Gen1, Value: 0x1 {09 09 7D 02 01 00 00 00 00}
	Option: Gen2, Value: 0x2 {09 09 7E 02 02 00 00 00 00}
End of Options {10 02}
Text: PEG2 {03 0B 34 02 35 02 36 02 00 00 00}
Setting: PEG2 - Gen X, Variable: 0xCF[1] {05 09 CF 00 01 79 02 7A 02}
	Option: Auto, Value: 0x0 {09 09 06 00 00 00 13 00 00}
	Option: Gen1, Value: 0x1 {09 09 7D 02 01 00 00 00 00}
	Option: Gen2, Value: 0x2 {09 09 7E 02 02 00 00 00 00}
End of Options {10 02}
Text: PEG3 {03 0B 37 02 38 02 39 02 00 00 00}
Setting: PEG3 - Gen X, Variable: 0xD0[1] {05 09 D0 00 01 7B 02 7C 02}
	Option: Auto, Value: 0x0 {09 09 06 00 00 00 13 00 00}
	Option: Gen1, Value: 0x1 {09 09 7D 02 01 00 00 00 00}
	Option: Gen2, Value: 0x2 {09 09 7E 02 02 00 00 00 00}
End of Options {10 02}
Subtitle:  {02 04 02 00}

---------------------------------------------------------------------------------------------------------------------------------------------------------

Setting: Active LFP, Variable: 0xA1[1] {05 09 A1 00 01 14 02 15 02}
	Option: No LVDS, Value: 0x0 {09 09 16 02 00 00 10 00 00}
	Option: Int-LVDS, Value: 0x1 {09 09 17 02 01 00 13 00 00}
	Option: SDVO LVDS, Value: 0x2 {09 09 18 02 02 00 10 00 00}
	Option: eDP Port-A, Value: 0x3 {09 09 19 02 03 00 10 00 00}
	Option: eDP Port-D, Value: 0x7 {09 09 1A 02 07 00 10 00 00}
End of Options {10 02}