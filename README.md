# Magic-Numbers

From: https://en.wikipedia.org/wiki/List_of_file_signatures
also used: https://www.garykessler.net/library/file_sigs.html


Main menu

WikipediaThe Free Encyclopedia
Search Wikipedia
Search
Create account
Log in

Personal tools
Contents hide
(Top)
See also
References
External links
List of file signatures

Article
Talk
Read
Edit
View history

Tools
From Wikipedia, the free encyclopedia
This is a dynamic list and may never be able to satisfy particular standards for completeness. You can help by adding missing items with reliable sources.

This article needs additional citations for verification. Please help improve this article by adding citations to reliable sources. Unsourced material may be challenged and removed.
Find sources: "List of file signatures" – news · newspapers · books · scholar · JSTOR (May 2021) (Learn how and when to remove this message)
This is a list of file signatures, data used to identify or verify the content of a file. Such signatures are also known as magic numbers or Magic Bytes.

Many file formats are not intended to be read as text. If such a file is accidentally viewed as a text file, its contents will be unintelligible. However, some file signatures can be recognizable when interpreted as text. The column ISO 8859-1 shows how the file signature appears when interpreted as text in the common ISO 8859-1 encoding, with unprintable characters represented as the control code abbreviation or symbol, or codepage 1252 character where available, or a box otherwise. In some cases the space character is shown as ␠ for clarity.

Hex signature	ISO 8859-1	Offset	Extension	Description
23 21	#!	0		Script or data to be passed to the program following the shebang (#!)[1]
02 00 5a 57 52 54 00 00 00 00 00 00 00 00 00 00	␂␀ZWRT␀␀␀␀␀␀␀␀␀␀	0	cwk	Claris Works word processing doc
00 00 02 00 06 04 06 00 08 00 00 00 00 00	␀␀␂␀␆␄␆␀␈␀␀␀␀␀	0	wk1	Lotus 1-2-3 spreadsheet (v1) file
00 00 1A 00 00 10 04 00 00 00 00 00	␀␀␚␀␀␊␄␀␀␀␀␀	0	wk3	Lotus 1-2-3 spreadsheet (v3) file
00 00 1A 00 02 10 04 00 00 00 00 00	␀␀␚␀␂␊␄␀␀␀␀␀	0	wk4
wk5	Lotus 1-2-3 spreadsheet (v4, v5) file
00 00 1A 00 05 10 04	␀␀␚␀␅␊␄	0	123	Lotus 1-2-3 spreadsheet (v9) file
00 00 03 F3	␀␀␃ó	0		Amiga Hunk executable file
00 00 49 49 58 50 52 (little-endian)
00 00 4D 4D 58 50 52 (big-endian)	␀␀IIXPR
␀␀MMXPR	0	qxd	Quark Express document
50 57 53 33	PWS3	0	psafe3	Password Gorilla Password Database
D4 C3 B2 A1 (little-endian)	ÔÃ²¡	0	pcap	Libpcap File Format[2]
A1 B2 C3 D4 (big-endian)	¡²ÃÔ
4D 3C B2 A1 (little-endian)	M<²¡	0	pcap	Libpcap File Format (nanosecond-resolution)[2]
A1 B2 3C 4D (big-endian)	¡²<M
0A 0D 0D 0A	␊␍␍␊	0	pcapng	PCAP Next Generation Dump File Format[3]
ED AB EE DB	í«îÛ	0	rpm	RedHat Package Manager (RPM) package[4]
53 51 4C 69 74 65 20 66
6F 72 6D 61 74 20 33 00	SQLite format 3␀	0	sqlitedb
sqlite
db	SQLite Database[5]
53 50 30 31	SP01	0	bin	Amazon Kindle Update Package[6]
49 57 41 44	IWAD	0	wad	internal WAD (main resource file of Doom)[7]
00	␀	0	PIC
PIF
SEA
YTR	IBM Storyboard bitmap file
Windows Program Information File
Mac Stuffit Self-Extracting Archive
IRIS OCR data file
00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00	␀␀␀␀␀␀␀␀
␀␀␀␀␀␀␀␀
␀␀␀␀␀␀␀␀	11	PDB	PalmPilot Database/Document File
BE BA FE CA	¾ºþÊ	0	DBA	Palm Desktop Calendar Archive
00 01 42 44	␀␁BD	0	DBA	Palm Desktop To Do Archive
00 01 44 54	␀␁DT	0	TDA	Palm Desktop Calendar Archive
54 44 46 24	TDF$	0	TDF$	Telegram Desktop File
54 44 45 46	TDEF	0	TDEF	Telegram Desktop Encrypted File
00 01 00 00	␀␁␀␀	0		Palm Desktop Data File (Access format)
00 00 01 00	␀␀␁␀	0	ico	Computer icon encoded in ICO file format[8]
69 63 6e 73	icns	0	icns	Apple Icon Image format
66 74 79 70 33 67	ftyp3g	4	3gp
3g2	3rd Generation Partnership Project 3GPP and 3GPP2 multimedia files
66 74 79 70 68 65 69 6366 74 79 70 6d	ftypheic	4	heic	High Efficiency Image Container (HEIC)
1F 9D	␟□	0	z
tar.z	compressed file (often tar zip) using Lempel-Ziv-Welch algorithm
1F A0	␟⍽	0	z
tar.z	Compressed file (often tar zip) using LZH algorithm
2D 68 6C 30 2D	-lh0-	2	lzh	Lempel Ziv Huffman archive file Method 0 (No compression)
2D 68 6C 35 2D	-lh5-	2	lzh	Lempel Ziv Huffman archive file Method 5 (8 KiB sliding window)
42 41 43 4B 4D 49 4B 45
44 49 53 4B	BACKMIKEDISK	0	bac	AmiBack Amiga Backup data file
49 4E 44 58	INDX	0	idx	AmiBack Amiga Backup index file
62 70 6C 69 73 74	bplist	0	plist	Binary Property List file
42 5A 68	BZh	0	bz2	Compressed file using Bzip2 algorithm
47 49 46 38 37 61
47 49 46 38 39 61	GIF87a
GIF89a	0	gif	Image file encoded in the Graphics Interchange Format (GIF)[9]
49 49 2A 00 (little-endian)	II*␀	0	tif
tiff	Tagged Image File Format (TIFF)[10]
4D 4D 00 2A (big-endian)	MM␀*
49 49 2A 00 10 00 00 00
43 52	II*␀␐␀␀␀CR	0	cr2	Canon RAW Format Version 2[11]
Canon's RAW format is based on TIFF.[12]
80 2A 5F D7	€*_×	0	cin	Kodak Cineon image
52 4E 43 01
52 4E 43 02	RNC␁
RNC␂	0		Compressed file using Rob Northen Compression (version 1 and 2) algorithm[13]
4E 55 52 55 49 4D 47
4E 55 52 55 50 41 4C	NURUIMG
NURUPAL	0	nui
nup	nuru ASCII/ANSI image and palette files[14]
53 44 50 58 (big-endian format)	SDPX	0	dpx	SMPTE DPX image
58 50 44 53 (little-endian format)	XPDS
76 2F 31 01	v/1␁	0	exr	OpenEXR image
42 50 47 FB	BPGû	0	bpg	Better Portable Graphics format[15]
FF D8 FF DB	ÿØÿÛ	0	jpg
jpeg	JPEG raw or in the JFIF or Exif file format[16]
FF D8 FF E0 00 10 4A 46
49 46 00 01	ÿØÿà␀␐JFIF␀␁
FF D8 FF EE	ÿØÿî
FF D8 FF E1 ?? ?? 45 78
69 66 00 00	ÿØÿá??Exif␀␀
FF D8 FF E0	ÿØÿà	0	jpg	JPEG raw or in the JFIF or Exif file format[16]
00 00 00 0C 6A 50 20 20 0D 0A 87 0A	␀␀␀␌jP␠␠␍␊‡␊	0	jp2
j2k
jpf
jpm
jpg2
j2c
jpc
jpx
mj2	JPEG 2000 format[17]
FF 4F FF 51	ÿOÿQ
71 6f 69 66	qoif	0	qoi	QOI - The “Quite OK Image Format”[18]
46 4F 52 4D ?? ?? ?? ??
49 4C 42 4D	FORM????ILBM	0
any	ilbm
lbm
ibm
iff	IFF Interleaved Bitmap Image
46 4F 52 4D ?? ?? ?? ??
38 53 56 58	FORM????8SVX	0
any	8svx
8sv
svx
snd
iff	IFF 8-Bit Sampled Voice
46 4F 52 4D ?? ?? ?? ??
41 43 42 4D	FORM????ACBM	0
any	acbm
iff	Amiga Contiguous Bitmap
46 4F 52 4D ?? ?? ?? ??
41 4E 42 4D	FORM????ANBM	0
any	anbm
iff	IFF Animated Bitmap
46 4F 52 4D ?? ?? ?? ??
41 4E 49 4D	FORM????ANIM	0
any	anim
iff	IFF CEL Animation
46 4F 52 4D ?? ?? ?? ??
46 41 58 58	FORM????FAXX	0
any	faxx
fax
iff	IFF Facsimile Image
46 4F 52 4D ?? ?? ?? ??
46 54 58 54	FORM????FTXT	0
any	ftxt
iff	IFF Formatted Text
46 4F 52 4D ?? ?? ?? ??
53 4D 55 53	FORM????SMUS	0
any	smus
smu
mus
iff	IFF Simple Musical Score
46 4F 52 4D ?? ?? ?? ??
43 4D 55 53	FORM????CMUS	0
any	cmus
mus
iff	IFF Musical Score
46 4F 52 4D ?? ?? ?? ??
59 55 56 4E	FORM????YUVN	0
any	yuvn
yuv
iff	IFF YUV Image
46 4F 52 4D ?? ?? ?? ??
46 41 4E 54	FORM????FANT	0
any	iff	Amiga Fantavision Movie
46 4F 52 4D ?? ?? ?? ??
41 49 46 46	FORM????AIFF	0
any	aiff
aif
aifc
snd
iff	Audio Interchange File Format
4C 5A 49 50	LZIP	0	lz	lzip compressed file[19]
30 37 30 37 30 37	070707	0	cpio	cpio archive file[20]
4D 5A	MZ	0	exe
dll
mui
sys
scr
cpl
ocx
ax
iec
ime
rs
tsp
fon
efi	DOS MZ executable and its descendants (including NE and PE)
5A 4D	ZM	0	exe	DOS ZM executable and its descendants (rare)
50 4B 03 04
50 4B 05 06 (empty archive)
50 4B 07 08 (spanned archive)	PK␃␄
PK␅␆
PK␇␈	0	zip
aar
apk
docx
epub
ipa
jar
kmz
maff
msix
odp
ods
odt
pk3
pk4
pptx
usdz
vsdx
xlsx
xpi	zip file format and formats based on it, such as EPUB, JAR, ODF, OOXML
52 61 72 21 1A 07 00	Rar!␚␇␀	0	rar	Roshal ARchive compressed archive v1.50 onwards[21]
52 61 72 21 1A 07 01 00	Rar!␚␇␁␀	0	rar	Roshal ARchive compressed archive v5.00 onwards[22]
7F 45 4C 46	␡ELF	0		Executable and Linkable Format
89 50 4E 47 0D 0A 1A 0A	‰PNG␍␊␚␊	0	png	Image encoded in the Portable Network Graphics format[23]
0E 03 13 01	␅␃␓␁	0	hdf4
h4	Data stored in version 4 of the Hierarchical Data Format.
89 48 44 46 0D 0A 1A 0A	‰HDF␍␊␚␊	0, 512, 1024, 2048, ...	hdf5
h5	Data stored in version 5 of the Hierarchical Data Format.
C9	É	0	com	CP/M 3 and higher with overlays[24]
CA FE BA BE	Êþº¾	0	class	Java class file, Mach-O Fat Binary
EF BB BF	ï»¿	0	txt
others	UTF-8 byte order mark, commonly seen in text files.[25][26][27]
FF FE	ÿþ	0	txt
others	UTF-16LE byte order mark, commonly seen in text files.[25][26][27]
FE FF	þÿ	0	txt
others	UTF-16BE byte order mark, commonly seen in text files.[25][26][27]
FF FE 00 00	ÿþ␀␀	0	txt
others	UTF-32LE byte order mark for text[25][27]
00 00 FE FF	␀␀þÿ	0	txt
others	UTF-32BE byte order mark for text[25][27]
2B 2F 76 38
2B 2F 76 39
2B 2F 76 2B
2B 2F 76 2F	+/v8
+/v9
+/v+
+/v/	0		UTF-7 byte order mark for text[28][27]
0E FE FF	␎þÿ	0	txt
others	SCSU byte order mark for text[28][27]
DD 73 66 73	Ýsfs	0		UTF-EBCDIC byte order mark for text[28][27]
FE ED FA CE	þíúÎ	0
0x1000		Mach-O binary (32-bit)
FE ED FA CF	þíúÏ	0
0x1000		Mach-O binary (64-bit)
FE ED FE ED	þíþí	0		JKS Javakey Store[29]
CE FA ED FE	Îúíþ	0		Mach-O binary (reverse byte ordering scheme, 32-bit)[30]
CF FA ED FE	Ïúíþ	0		Mach-O binary (reverse byte ordering scheme, 64-bit)[30]
25 21 50 53	%!PS	0	ps	PostScript document
25 21 50 53 2D 41 64 6F 62 65 2D 33 2E 30 20 45 50 53 46 2D 33 2E 30	%!PS-Adobe-3.0 ESPF-3.0	0	eps
epsf	Encapsulated PostScript file version 3.0[31]
25 21 50 53 2D 41 64 6F 62 65 2D 33 2E 31 20 45 50 53 46 2D 33 2E 30	%!PS-Adobe-3.1 ESPF-3.0	0	eps
epsf	Encapsulated PostScript file version 3.1[32]
49 54 53 46 03 00 00 00
60 00 00 00	ITSF␃␀␀␀`␀␀␀	0	chm	MS Windows HtmlHelp Data
3F 5F	?_	0	hlp	Windows 3.x/95/98 Help file
25 50 44 46 2D	%PDF-	0	pdf	PDF document[33]
30 26 B2 75 8E 66 CF 11
A6 D9 00 AA 00 62 CE 6C	0&²uŽfÏ␑¦Ù␀ª␀bÎl	0	asf
wma
wmv	Advanced Systems Format[34]
24 53 44 49 30 30 30 31	$SDI0001	0		System Deployment Image, a disk image format used by Microsoft
4F 67 67 53	OggS	0	ogg
oga
ogv	Ogg, an open source media container format
38 42 50 53	8BPS	0	psd	Photoshop Document file, Adobe Photoshop's native file format
52 49 46 46 ?? ?? ?? ??
57 41 56 45	RIFF????WAVE	0	wav	Waveform Audio File Format[35]
52 49 46 46 ?? ?? ?? ??
41 56 49 20	RIFF????AVI␠	0	avi	Audio Video Interleave video format[36]
FF FB
FF F3
FF F2	ÿû
ÿó
ÿò	0	mp3	MPEG-1 Layer 3 file without an ID3 tag or with an ID3v1 tag (which is appended at the end of the file)
49 44 33	ID3	0	mp3	MP3 file with an ID3v2 container
42 4D	BM	0	bmp
dib	BMP file, a bitmap format used mostly in the Windows world
43 44 30 30 31	CD001	0x8001
0x8801
0x9001	iso	ISO9660 CD/DVD image file[37]
43 44 30 30 31	CD001	0x5EAC9	cdi	CD-i CD image file
6D 61 69 6E 2E 62 73	main.bs	0	mgw	Nintendo Game & Watch image file
4E 45 53	NES	0	nes	Nintendo Entertainment System image file
A0 32 41 A0 A0 A0	2A	0x165A4	d64	Commodore 64 1541 disk image (D64 format)
47 53 52 2D 31 35 34 31	GCR-1541	0	g64	Commodore 64 1541 disk image (G64 format)
A0 33 44 A0 A0	3D	0x61819	d81	Commodore 64 1581 disk image (D81 format)
43 36 34 20 74 61 70 65 20 69 6D 61 67 65 20 66 69 6C 65	C64 tape image file	0	t64	Commodore 64 tape image
43 36 34 20 43 41 52 54 52 49 44 47 45 20 20 20	C64 CARTRIDGE	0	crt	Commodore 64 cartridge image
53 49 4D 50 4C 45 20 20
3D 20 20 20 20 20 20 20
20 20 20 20 20 20 20 20
20 20 20 20 20 54	SIMPLE␠␠
=␠␠␠␠␠␠␠
␠␠␠␠␠␠␠␠
␠␠␠␠␠T	0	fits	Flexible Image Transport System (FITS)[38]
66 4C 61 43	fLaC	0	flac	Free Lossless Audio Codec[39]
4D 54 68 64	MThd	0	mid
midi	MIDI sound file[40]
D0 CF 11 E0 A1 B1 1A E1	ÐÏ␑à¡±␚á	0	doc
xls
ppt
msi
msg	Compound File Binary Format, a container format defined by Microsoft COM. It can contain the equivalent of files and directories. It is used by Windows Installer and for documents in older versions of Microsoft Office.[41] It can be used by other programs as well that rely on the COM and OLE API's.
64 65 78 0A 30 33 35 00	dex␊035␀	0	dex	Dalvik Executable
4B 44 4D	KDM	0	vmdk	VMDK files[42][43]
23 20 44 69 73 6B 20 44 65 73 63 72 69 70 74 6F	# Disk Descripto	0	vmdk	VMware 4 Virtual Disk description file (split disk)
43 72 32 34	Cr24	0	crx	Google Chrome extension[44] or packaged app[45]
41 47 44 33	AGD3	0	fh8	FreeHand 8 document[46][47]
05 07 00 00 42 4F 42 4F
05 07 00 00 00 00 00 00
00 00 00 00 00 01	␅␇␀␀BOBO
␅␇␀␀␀␀␀␀
␀␀␀␀␀␁	0	cwk	AppleWorks 5 document
06 07 E1 00 42 4F 42 4F
06 07 E1 00 00 00 00 00
00 00 00 00 00 01	␆␇á␀BOBO
␆␇á␀␀␀␀␀
␀␀␀␀␀␁	0	cwk	AppleWorks 6 document
45 52 02 00 00 00	ER␂␀␀␀	0	toast	Roxio Toast disc image file
8B 45 52 02 00 00 00	‹ER␂␀␀␀
6B 6F 6C 79	koly	end–512	dmg	Apple Disk Image file
78 61 72 21	xar!	0	xar	eXtensible ARchive format[48]
50 4D 4F 43 43 4D 4F 43	PMOCCMOC	0	dat	Windows Files And Settings Transfer Repository[49] See also USMT 3.0 (Win XP)[50] and USMT 4.0 (Win 7)[51] User Guides
4E 45 53 1A	NES␚	0	nes	Nintendo Entertainment System ROM file[52]
75 73 74 61 72 00 30 30
75 73 74 61 72 20 20 00	ustar␀00
ustar␠␠␀	257	tar	tar archive[53]
4F 41 52 ??	OAR?	0	oar	OAR file archive format, where ?? is the format version.
74 6F 78 33	tox3	0	tox	Open source portable voxel file[54]
4D 4C 56 49	MLVI	0	MLV	Magic Lantern Video file[55]
44 43 4D 01 50 41 33 30
50 41 33 30	DCM␁PA30
PA30	0		Windows Update Binary Delta Compression file[56]
37 7A BC AF 27 1C	7z¼¯'␜	0	7z	7-Zip File Format
1F 8B	␟‹	0	gz
tar.gz	GZIP compressed file[57]
FD 37 7A 58 5A 00	ý7zXZ␀	0	xz
tar.xz	XZ compression utility
using LZMA2 compression
04 22 4D 18	␄"M␘	0	lz4	LZ4 Frame Format[58]
Remark: LZ4 block format does not offer any magic bytes.[59]
4D 53 43 46	MSCF	0	cab	Microsoft Cabinet file
53 5A 44 44 88 F0 27 33	SZDDˆð'3	0	??_	Microsoft compressed file in Quantum format, used prior to Windows XP. File can be decompressed using Extract.exe or Expand.exe distributed with earlier versions of Windows. After compression, the last character of the original filename extension is replaced with an underscore, e.g. ‘Setup.exe’ becomes ‘Setup.ex_’.
46 4C 49 46	FLIF	0	flif	Free Lossless Image Format
1A 45 DF A3	␚Eß£	0	mkv
mka
mks
mk3d
webm	Matroska media container, including WebM
4D 49 4C 20	MIL␠	0	stg	"SEAN : Session Analysis" Training file. Also used in compatible software "Rpw : Rowperfect for Windows" and "RP3W : ROWPERFECT3 for Windows".
41 54 26 54 46 4F 52 4D
 ?? ?? ?? ?? 44 4A 56	AT&TFORM????DJV	0	djvu
djv	DjVu document
The following byte is either 55 (U) for single-page or 4D (M) for multi-page documents.
30 82	0‚	0	der	DER encoded X.509 certificate
2D 2D 2D 2D 2D 42 45 47 49 4E 20 43 45 52 54 49 46 49 43 41 54 45 2D 2D 2D 2D 2D	-----BEGIN CERTIFICATE-----	0	crt
pem	PEM encoded X.509 certificate
2D 2D 2D 2D 2D 42 45 47 49 4E 20 43 45 52 54 49 46 49 43 41 54 45 20 52 45 51 55 45 53 54 2D 2D 2D 2D 2D	-----BEGIN CERTIFICATE REQUEST-----	0	csr
pem	PEM encoded X.509 Certificate Signing Request
2D 2D 2D 2D 2D 42 45 47 49 4E 20 50 52 49 56 41 54 45 20 4B 45 59 2D 2D 2D 2D 2D	-----BEGIN PRIVATE KEY-----	0	key
pem	PEM encoded X.509 PKCS#8 private key
2D 2D 2D 2D 2D 42 45 47 49 4E 20 44 53 41 20 50 52 49 56 41 54 45 20 4B 45 59 2D 2D 2D 2D 2D	-----BEGIN DSA PRIVATE KEY-----	0	key
pem	PEM encoded X.509 PKCS#1 DSA private key
2D 2D 2D 2D 2D 42 45 47 49 4E 20 52 45 41 20 50 52 49 56 41 54 45 20 4B 45 59 2D 2D 2D 2D 2D	-----BEGIN RSA PRIVATE KEY-----	0	key
pem	PEM encoded X.509 PKCS#1 RSA private key
50 75 54 54 59 2D 55 73 65 72 2D 4B 65 79 2D 46 69 6C 65 2D 32 3A	PuTTY-User-Key-File-2:	0	ppk	PuTTY private key file version 2
50 75 54 54 59 2D 55 73 65 72 2D 4B 65 79 2D 46 69 6C 65 2D 33 3A	PuTTY-User-Key-File-3:	0	ppk	PuTTY private key file version 3
2D 2D 2D 2D 2D 42 45 47 49 4E 20 4F 50 45 4E 53 53 48 20 50 52 49 56 41 54 45 20 4B 45 59 2D 2D 2D 2D 2D	-----BEGIN OPENSSH PRIVATE KEY-----	0		OpenSSH private key file
2D 2D 2D 2D 2D 42 45 47 49 4E 20 53 53 48 32 20 4B 45 59 2D 2D 2D 2D 2D	-----BEGIN SSH2 PUBLIC KEY-----	0	pub	OpenSSH public key file
44 49 43 4D	DICM	128	dcm	DICOM Medical File Format
77 4F 46 46	wOFF	0	woff	WOFF File Format 1.0[60]
77 4F 46 32	wOF2	0	woff2	WOFF File Format 2.0[61]
3C 3F 78 6D 6C 20	<?xml␠	0
after BOM	xml	eXtensible Markup Language[26][62]
3C 00 3F 00 78 00 6D 00
6C 00 20	<␀?␀x␀m␀l␀␠␀
00 3C 00 3F 00 78 00 6D
00 6C 00 20	␀<␀?␀x␀m␀l␀␠
3C 00 00 00 3F 00 00 00
78 00 00 00 6D 00 00 00
6C 00 00 00 20 00 00 00	<␀␀␀?␀␀␀
x␀␀␀m␀␀␀
l␀␀␀␠␀␀␀
00 00 00 3C 00 00 00 3F
00 00 00 78 00 00 00 6D
00 00 00 6C 00 00 00 20	␀␀␀<␀␀␀?
␀␀␀x␀␀␀m
␀␀␀l␀␀␀␠
4C 6F A7 94 93 40	Lo§”“@
00 61 73 6D	␀asm	0	wasm	WebAssembly binary format[63]
CF 84 01	Ï„␁	0	lep	Lepton compressed JPEG image[64]
43 57 53	CWS	0	swf	Adobe Flash .swf
46 57 53	FWS
21 3C 61 72 63 68 3E 0A	!<arch>␊	0	deb	linux deb file
52 49 46 46 ?? ?? ?? ??
57 45 42 50	RIFF????WEBP	0	webp	Google WebP image file, where ?? ?? ?? ?? is the file size. More information on WebP File Header
27 05 19 56	'␅␙V	0		U-Boot / uImage. Das U-Boot Universal Boot Loader.[65]
7B 5C 72 74 66 31	{\rtf1	0	rtf	Rich Text Format
54 41 50 45	TAPE	0		Microsoft Tape Format
47	G	0
0xBC
0x178
...
(every 188th byte)	ts
tsv
tsa
mpg
mpeg	MPEG Transport Stream (MPEG-2 Part 1)[66]
00 00 01 BA	␀␀␁º	0	m2p
vob
mpg
mpeg	MPEG Program Stream (MPEG-1 Part 1 (essentially identical) and MPEG-2 Part 1)
00 00 01 B3	␀␀␁³	0	mpg
mpeg	MPEG-1 video and MPEG-2 video (MPEG-1 Part 2 and MPEG-2 Part 2)
66 74 79 70 69 73 6F 6D	ftypisom	4	mp4	ISO Base Media file (MPEG-4)
66 74 79 70 4D 53 4E 56	ftypMSNV	4	mp4	MPEG-4 video file
78 01	x␁	0	zlib	No Compression (no preset dictionary)
78 5E	x^	Best speed (no preset dictionary)
78 9C	xœ	Default Compression (no preset dictionary)
78 DA	xÚ	Best Compression (no preset dictionary)
78 20	x␠	No Compression (with preset dictionary)
78 7D	x}	Best speed (with preset dictionary)
78 BB	x»	Default Compression (with preset dictionary)
78 F9	xù	Best Compression (with preset dictionary)
62 76 78 32	bvx2	0	lzfse	LZFSE - Lempel-Ziv style data compression algorithm using Finite State Entropy coding. OSS by Apple.[67]
4F 52 43	ORC	0	orc	Apache ORC (Optimized Row Columnar) file format
4F 62 6A 01	Obj␁	0	avro	Apache Avro binary file format
53 45 51 36	SEQ6	0	rc	RCFile columnar file format
3C 72 6F 62 6C 6F 78 21	<roblox!	0	rbxl	Roblox place file [68]
65 87 78 56	e‡xV	0	p25
obt	PhotoCap Object Templates
55 55 AA AA	UUªª	0	pcv	PhotoCap Vector
78 56 34	xV4	0	pbt
pdt
pea
peb
pet
pgt
pict
pjt
pkt
pmt	PhotoCap Template
50 41 52 31	PAR1	0		Apache Parquet columnar file format
45 4D 58 32	EMX2	0	ez2	Emulator Emaxsynth samples
45 4D 55 33	EMU3	0	ez3
iso	Emulator III synth samples
1B 4C 75 61	␛Lua	0	luac	Lua bytecode[69]
62 6F 6F 6B 00 00 00 00
6D 61 72 6B 00 00 00 00	book␀␀␀␀mark␀␀␀␀	0	alias	macOS file Alias[70] (Symbolic link)
5B 5A 6F 6E 65 54 72 61
6E 73 66 65 72 5D	[ZoneTransfer]	0	Identifier	Microsoft Zone Identifier for URL Security Zones[71][72]
52 65 63 65 69 76 65 64
3A	Received:	0	eml	Email Message var5[citation needed]
20 02 01 62 A0 1E AB 07
02 00 00 00	␠␂␁b⍽␞«␇␂␀␀␀	0	tde	Tableau Datasource
37 48 03 02 00 00 00 00
58 35 30 39 4B 45 59	7H␃␂␀␀␀␀X509KEY	0	kdb	KDB file
85 ?? ?? 03	…??␃	0	pgp	PGP file [73]
28 B5 2F FD	(µ/ý	0	zst	Zstandard compress[74][75]
52 53 56 4B 44 41 54 41	RSVKDATA	0	rs	QuickZip rs compressed archive[76][77]
3A 29 0A	:)␊	0	sml	Smile file
4A 6F 79 21	Joy!	0		Preferred Executable Format
31 0A 30 30	1␊00	0	srt	SubRip File
34 12 AA 55	4␒ªU	0	vpk	VPK file, used to store game data for some Source Engine games
2A 2A 41 43 45 2A 2A	**ACE**	7	ace	ACE (compressed file format)[citation needed]
60 EA	`ê	0	arj	ARJ
49 53 63 28	ISc(	0	cab	InstallShield CAB Archive File
4B 57 41 4A	KWAJ	0	??_	Windows 3.1x Compressed File
53 5A 44 44	SZDD	0	??_	Windows 9x Compressed File
5A 4F 4F	ZOO	0	zoo	Zoo (file format)
50 31 0A	P1␊	0	pbm	Portable bitmap ASCII
50 34 0A	P4␊	0	pbm	Portable bitmap binary
50 32 0A	P2␊	0	pgm	Portable Gray Map ASCII
50 35 0A	P5␊	0	pgm	Portable Gray Map binary
50 33 0A	P3␊	0	ppm	Portable Pixmap ASCII
50 36 0A	P6␊	0	ppm	Portable Pixmap binary
D7 CD C6 9A	×ÍÆš	0	wmf	Windows Metafile
67 69 6D 70 20 78 63 66	gimp xcf	0	xcf	XCF (file format)
2F 2A 20 58 50 4D 20 2A
2F	/* XPM */	0	xpm	X PixMap
41 46 46	AFF	0	aff	Advanced Forensics Format
45 56 46 32	EVF2	0	Ex01	EnCase EWF version 2 format
45 56 46	EVF	0	e01	EnCase EWF version 1 format
51 46 49	QFI	0	qcow	qcow file format
52 49 46 46 ?? ?? ?? ??
41 43 4F 4E	RIFF????ACON	0	ani	Animated cursor
52 49 46 46 ?? ?? ?? ??
43 44 44 41	RIFF????CDDA	0	cda	.cda file
52 49 46 46 ?? ?? ?? ??
51 4C 43 4D	RIFF????QLCM	0	qcp	Qualcomm PureVoice file format
52 49 46 58 ?? ?? ?? ??
46 47 44 4D (big-endian)	RIFX????FGDM	0	dcr	Adobe Shockwave[78][79][80]
58 46 49 52 ?? ?? ?? ??
4D 44 47 46 (little-endian)	XFIR????MDGF
52 49 46 58 ?? ?? ?? ??
4D 56 39 33 (big-endian)	RIFX????MV93	0	dir
dxr
drx	Macromedia Director file format[81][79][80]
58 46 49 52 ?? ?? ?? ??
33 39 56 4D (little-endian)	XFIR????39VM
46 4C 56	FLV	0	flv	Flash Video file
3C 3C 3C 20 4F 72 61 63
6C 65 20 56 4D 20 56 69
72 74 75 61 6C 42 6F 78
20 44 69 73 6B 20 49 6D
61 67 65 20 3E 3E 3E	<<< Orac
le VM Vi
rtualBox
 Disk Im
age >>>	0	vdi	VirtualBox Virtual Hard Disk file format
63 6F 6E 65 63 74 69 78	conectix	0	vhd	Windows Virtual PC Virtual Hard Disk file format[82]
76 68 64 78 66 69 6C 65	vhdxfile	0	vhdx	Windows Virtual PC Windows 8 Virtual Hard Disk file format
49 73 5A 21	IsZ!	0	isz	Compressed ISO image
44 41 41	DAA	0	daa	Direct Access Archive PowerISO
4C 66 4C 65	LfLe	0	evt	Windows Event Viewer file format
45 6C 66 46 69 6C 65	ElfFile	0	evtx	Windows Event Viewer XML file format
73 64 62 66	sdbf	8	sdb	Windows customized database
50 4D 43 43	PMCC	0	grp	Windows 3.x Program Manager Program Group file format
4B 43 4D 53	KCMS	0	icm	ICC profile
72 65 67 66	regf	0	dat
hiv	Windows Registry file
21 42 44 4E	!BDN	0	pst	Microsoft Outlook Personal Storage Table file
44 52 41 43 4F	DRACO	0	drc	3D model compressed with Google Draco[83]
47 52 49 42	GRIB	0	grib
grib2	Gridded data (commonly weather observations or forecasts) in the WMO GRIB or GRIB2 format[84]
42 4C 45 4E 44 45 52	BLENDER	0	blend	Blender File Format[85]
00 00 00 0C 4A 58 4C 20 0D 0A 87 0A	␀␀␀␌JXL␠␍␊‡␊	0	jxl	Image encoded in the JPEG XL format[86]
FF 0A	ÿ␊
00 01 00 00 00	␀␁␀␀␀	0	ttf
tte
dfont	TrueType font
4F 54 54 4F	OTTO	0	otf	OpenType font[87]
23 25 4D 6F 64 75 6C 65	#%Module	0		Modulefile for Environment Modules[88]
4D 53 57 49 4D 00 00 00
D0 00 00 00 00	MSWIM␀␀␀Ð␀␀␀␀	0	wim
swm
esd	Windows Imaging Format file
21 2D 31 53 4C 4F 42 1F	!-1SLOB␟	0	slob	Slob (sorted list of blobs) is a read-only, compressed data store with dictionary-like interface[89]
AC ED	¬í	0		Serialized Java Data[90]
43 72 65 61 74 69 76 65 20 56 6F 69 63 65 20 46 69 6C 65 1A 1A 00	Creative Voice File	0	voc	Creative Voice file
2E 73 6E 64	.snd	0	au
snd	Au audio file format
DB 0A CE 00		0		OpenGL Iris Perfomer .PFB (Performer Fast Binary)[91]
48 5a 4c 52 00 00 00 18	HZLR	0	hazelrules	Noodlesoft Hazel [92]
46 4C 68 64	FLhd	0	flp	FL Studio Project File
31 30 4C 46	10LF	0	flm	FL Studio Mobile Project File
52 4b 4d 43 32 31 30	RKMC210	0		Vormetric Encryption DPM Version 2.1 Header[93]
00 01 00 00 4D 53 49 53 41 4D 20 44 61 74 61 62 61 73 65	␀␁␀␀MSISAM Database	0	mny	Microsoft Money file
00 01 00 00 53 74 61 6E 64 61 72 64 20 41 43 45 20 44 42	␀␁␀␀Standard ACE DB	0	accdb	Microsoft Access 2007 Database
00 01 00 00 53 74 61 6E 64 61 72 64 20 4A 65 74 20 44 42	␀␁␀␀Standard Jet DB	0	mdb	Microsoft Access Database
01 FF 02 04 03 02	␁ÿ␂␄␃␂	0	drw	Micrografx vector graphic file
02 64 73 73	␂dss	0	dss	Digital Speech Standard (Olympus, Grundig, & Phillips) v2
03 64 73 73	␃dss	0	dss	Digital Speech Standard (Olympus, Grundig, & Phillips) v3
03 00 00 00 41 50 50 52	␃␀␀␀APPR	0	adx	Approach index file
06 06 ED F5 D8 1D 46 E5 BD 31 EF E7 FE 74 B7 1D	␆␆íõØ␝Få½1ïçþt·␝	0	indd	Adobe InDesign document
06 0E 2B 34 02 05 01 01 0D 01 02 01 01 02	␆␎+4␂␅␁␁␍␁␂␁␁␂	0-65535 (run-in)	mxf	Material Exchange Format file
07 53 4B 46	␇SKF	0	skf	SkinCrafter skin file
07 64 74 32 64 64 74 64	␇dt2ddtd	0	dtd	DesignTools 2D Design file
0A 16 6F 72 67 2E 62 69 74 63 6F 69 6E 2E 70 72	␊␖org.bitcoin.pr	0	wallet	MultiBit Bitcoin wallet file
0D 44 4F 43	␍DOC	0	doc	DeskMate Document file
0E 4E 65 72 6F 49 53 4F	␎NeroISO	0	nri	Nero CD Compilation
0E 57 4B 53	␎WKS	0	wks	DeskMate Worksheet
0F 53 49 42 45 4C 49 55 53	␏SIBELIUS	0	sib	Sibelius Music - Score file
23 20 4D 69 63 72 6F 73 6F 66 74 20 44 65 76 65 6C 6F 70 65 72 20 53 74 75 64 69 6F	# Microsoft Developer Studio	0	dsp	Microsoft Developer Studio project file
23 21 41 4D 52	#!AMR	0	amr	Adaptive Multi-Rate ACELP (Algebraic Code Excited Linear Prediction) Codec, commonly audio format with GSM cell phones.
23 21 53 49 4C 4B 0A	#!SILK␊	0	sil	Audio compression format developed by Skype
23 3F 52 41 44 49 41 4E 43 45 0A	#?RADIANCE␊	0	hdr	Radiance High Dynamic Range image file
23 40 7E 5E	#@~^	0	vbe	VBScript Encoded script
0D F0 1D C0	␍ð�À	0	cdb	MikroTik WinBox Connection Database (Address Book)
23 45 58 54 4D 33 55	#EXTM3U	0	m3u
m3u8

Multimedia playlist
6D 64 66 00	mdf␀	0	m	M2 Archive, used by game developer M2
4B 50 4B 41	KPKA	0	pak	Capcom RE Engine game data archives
41 52 43	ARC	0	arc	Capcom MT Framework game data archives
D0 4F 50 53	ÐOPS	0	pl	Interleaf PrinterLeaf / WorldView document format (now Broadvision QuickSilver)
6E 2B 31 00	n+1	344	nii	Single file NIfTI format, used extensively in biomedical imaging.
6E 69 31 00	ni1	344	hdr	Header file of a .hdr/.img pair in NIfTI format, used extensively in biomedical imaging.
52 41 46 36 34	RAF64	0		Report Builder file from Digital Metaphors
56 49 53 33	VIS3	0		Resource file Visionaire 3.x Engine
4D 53 48 7C
42 53 48 7C	MSH|
BSH|	0	hl7	Health Level Seven (HL7) Standard for electronic data exchange [1]
70 77 72 64 61 74 61	pwrdata	0	pwrdata	SAP Power Monitor (version 1.1.0 and higher) data file
1a 08	..	0	arc	ARC archive file
2d 2d 2d 2d 2d 42 45 47 49 4e 20 50 47 50 20 50 55 42 4c 49 43 20 4b 45 49 20 42 4c 4f 43 4b 2d 2d 2d 2d 2d	-----BEGIN PGP PUBLIC KEY BLOCK-----	0	asc	Armored PGP public key
3a 42 61 73 65 20	:Base	0	cnt	Windows 3.x - Windows 95 Help Contents
52 49 46 46 ?? ?? ?? ?? 56 44 52 4d	RIFF????VDRM	0	vdr	VirtualDub
52 59 46 46 ?? ?? ?? ?? 54 52 49 44	RIFF????TRID	0	trd	TrID
52 49 46 46 ?? ?? ?? ?? 73 68 77 34	RIFF????shw4	0	shw	Corel SHOW! 4.0
52 49 46 46 ?? ?? ?? ?? 73 68 77 35	RIFF????shw5	0	shw	Corel SHOW! 5.0
52 49 46 46 ?? ?? ?? ?? 73 68 72 35	RIFF????shr5	0	shr	Corel SHOW! 5.0 player
52 49 46 46 ?? ?? ?? ?? 73 68 62 35	RIFF????shb5	0	shb	Corel SHOW! 5.0 background
52 49 46 46 ?? ?? ?? ?? 52 4d 4d 50	RIFF????RMMP	0	mmm	MacroMind Multimedia Movie or Microsoft Multimedia Movie
41 53 54 4d 2d 45 35 37	ASTM-E57	0	e57	ASTM E57 3D file format
See also
List of file formats
Magic number (programming)
Substitute character (for the 1Ah (^Z) "end-of-file" marker used in many signatures)
file (command)
References
 "execve(2): execute program - Linux man page". linux.die.net. Retrieved 2022-07-12.
 "Libpcap File Format". Retrieved 2018-06-19.
 "PCAP Next Generation Dump File Format". Retrieved 2018-06-19.
 "A. Format of the RPM file". Retrieved 2017-02-15.[permanent dead link]
 "Database File Format". Retrieved 2018-11-16.
 "GitHub - NiLuJe/KindleTool: Tool for creating/extracting Kindle updates and more". GitHub. Retrieved 2017-02-15.
 "IWAD". Retrieved 2022-07-05.
 Icons (at MSDN)
 GRAPHICS INTERCHANGE FORMAT(sm) Version 89a
 "TIFF, Revision 6.0". Sustainability of Digital Formats: Planning for Library of Congress Collections. The Library of Congress. 2022-04-06. Retrieved 2022-07-12.
 Computer Knowledge. "File Extension .CR2 Details". filext.com.
 "Inside the Canon RAW format version 2, understanding .CR2 file format and files produced by Canon EOS Digital Camera". free.fr.
 "Rob Northen compression". Sega Retro. 11 August 2020. Retrieved 18 January 2024.
 "domsson/nuru". github.com. 9 September 2023.
 Bellard, Fabrice (2015). "BPG Image format".
 "Overview of JPEG 1".
 "Overview of JPEG 2000".
 "qoi-specification" (PDF).
 "Lzip Compressed Format and the 'application/lzip' Media Type". Ietf Datatracker. section 2.
 "Format of cpio archives". Retrieved 2022-07-05.
 TechNote.txt: RAR version 4.00 - Technical information (Technical report). 2010-12-01. The marker block is actually considered as a fixed byte sequence: 0x52 0x61 0x72 0x21 0x1a 0x07 0x00
 "RAR 5.0 archive format". Retrieved 2023-10-19.
 PNG (Portable Network Graphics) Specification Version 1.0. IETF. doi:10.17487/RFC2083. RFC 2083.
 Elliott, John C.; Lopushinsky, Jim (2002) [1998-04-11]. "CP/M 3.0 COM file header". Seasip.info. Archived from the original on 2016-08-30. Retrieved 2016-08-29.
 "Faq - Utf-8, Utf-16, Utf-32 & Bom".
 "How to : Load XML from File with Encoding Detection". 10 April 2016.
 "SDL Documentation".
 Honerman, Tom (January 2, 2021). "Clarify guidance for use of a BOM as a UTF-8 encoding signature" (PDF).
 "JKS". Javakey Store.
 "Mac Developer Library". apple.com.
 "Encapsulated PostScript (EPS) File Format, Version 3.x". Library of Congress. 10 May 2022. Retrieved 2022-07-05.
 "Encapsulated PostScript (EPS) File Format, Version 3.x". Library of Congress. 10 May 2022. Retrieved 2022-07-05.
 "File command PDF Magic format". GitHub. Retrieved 2018-11-06.
 "ASF (Advanced Systems Format)". 6 April 2007.
 "WAVE Audio File Format". Sustainability of Digital Formats: Planning for Library of Congress Collections. The Library of Congress. 2022-04-19. Retrieved 2022-07-12.
 "AVI (Audio Video Interleaved) File Format". Sustainability of Digital Formats: Planning for Library of Congress Collections. The Library of Congress. 2016-03-09. Retrieved 2022-07-12.
 Gary C. Kessler (21 October 2012). "File Signatures Table". Retrieved 28 December 2012.
 "Flexible Image Transport System (FITS), Version 3.0 - File type signifiers". Library of Congress. 2012-09-26. Retrieved 16 June 2021.
 Josh Coalson. "FLAC— format". Retrieved 16 June 2021. "fLaC", the FLAC stream marker in ASCII, meaning byte 0 of the stream is 0x66, followed by 0x4C 0x61 0x43
 "File Signature Database: mid File Signatures". filesignatures.net.[dead link]
 "Developing a tool to recognise MS Office file types ( .doc, .xls, .mdb, .ppt )". social.msdn.microsoft.com. Archived from the original on 2014-08-09. Retrieved 2014-07-28.
 "What Files Make Up a Virtual Machine?". VMware.
 "VMware Virtual Disks Virtual Disk Format 1.1". VMware.
 "CRX Package Format". chrome.com.
 "CRX Package Format". chrome.com.
 "[Pythonmac-SIG] Discovering file type". python.org. 10 February 2005.
 Kehl, Ken. "Re: What is the suffix for Freehand files?". Google Groups.
 "xar - xarformat.wiki". code.google.com.
 "Easily Restore Your Computer With File and Settings Transfer Wizard XP (Part 1)". howtogeek.com. 27 August 2007.
 "User State Migration Tool 3.0". microsoft.com. Microsoft.
 "User State Migration Tool 4.0 User's Guide". microsoft.com. Microsoft. 29 June 2010.
 "NESRomTool::NES ROM Quickstart". sadistech.com.
 "GNU tar 1.28: Basic Tar Format". gnu.org.
 "UVOX Universal Voxel Translator - Man Page". tox.land. Archived from the original on 2016-05-08. Retrieved 2015-06-29.
 "RAW Format v2.0 - Google Sheets". google.com.
 "Using Binary Delta Compression (BDC) Technology to Update Windows Operating Systems". Microsoft. 10 June 2005. Retrieved 15 March 2015.
 Deutsch, L. Peter (May 1996). "Member header and trailer". GZIP file format specification version 4.3. p. 6. doi:10.17487/RFC1952. RFC 1952. Retrieved 2018-10-29.
 Collet, Yann (19 November 2021). "LZ4 Frame format". github.com.
 Collet, Yann (19 November 2021). "LZ4 Block Format". github.com.
 "WOFF 1". w3.org. 13 December 2012. Retrieved 18 January 2024.
 "WOFF 2". w3.org. 13 December 2012. Retrieved 18 January 2024.
 "Extensible Markup Language (XML) 1.0 (Fifth Edition)".
 "WebAssembly/design". GitHub. Retrieved 2016-11-01.
 "Lepton image compression: saving 22% losslessly from images at 15MB/s". Dropbox.
 "How to Extract an uImage". Archived from the original on 2017-02-25. Retrieved 2017-02-24.
 "An introduction to MPEG-TS" (PDF).
 "lzfse/lzfse". GitHub. Retrieved 2018-10-16.
 "ROBLOX File Format" (PDF). www.classy-studios.com. Retrieved 5 September 2023.
 Laurie, Dirk (2013). "Lua 5.2 Bytecode and Virtual Machine".
 "Mac OS X - ForensicsWiki". www.forensicswiki.org. Retrieved 2018-09-22.
 "About URL Security Zones (Windows)". learn.microsoft.com. 15 August 2017. Retrieved 18 January 2024.
 "libyal/libfsntfs". GitHub. Retrieved 2018-09-22.
 "gnupg - Is it a coincidence that the first 4 bytes of a PGP/GPG file are ellipsis, smile, female sign and a heart? - Information Security Stack Exchange)". security.stackexchange.com. Retrieved 2020-06-05.
 Collet, Yann; Kucherawy, Murray (October 2018). "Zstandard Frames". Zstandard Compression and the application/zstd Media Type. sec. 3.1.1. doi:10.17487/RFC8478. RFC 8478. Retrieved 2018-10-29.
 "Magic numbering scheme (zstd project issue tracker)". GitHub. Retrieved 2018-10-29.
 "RS File Extension". filext.com. Retrieved 2020-09-18.
 "Quickzip.org (WebArchive)". Archived from the original on 2005-04-03. Retrieved 2020-09-18.
 "DCR format - reverseShockwave".
 "Shockwave (Director)". fileformats.archiveteam.org. Archived from the original on 11 February 2020. Retrieved 15 January 2022.
 "Projector EXE to Shockwave DCR".
 "Dir format - reverseShockwave".
 "Virtual Hard Disk Image Format Specification".
 "Draco Bitstream Specification". google.github.io. Archived from the original on 2021-01-18. Retrieved 2021-01-18.
 "A GUIDE TO THE CODE FORM FM 92-IX Ext. GRIB". Archived from the original on 2021-05-02. Retrieved 2021-05-02.
 "The mystery of the blend". 2015-04-18. Archived from the original on 2015-04-18. Retrieved 2021-05-07.
 "GitHub - JPEG/JPEG XL Reference Software". github.com. Retrieved 2021-08-11.
 "The OpenType Font File". docs.microsoft.com. 9 December 2021. Retrieved 2022-02-07.
 "Environment Modules Documentation: modulefile". Retrieved 2021-08-19.
 GitHub - itkach/slob: Data store for Aard 2
 "Java Object Serialization Specification: 6 - Object Serialization Stream Protocol".
 "J3k0/OpenPFB". GitHub. 25 June 2022.
 "Noodlesoft – Noodlesoft – Simply Useful Software". www.noodlesoft.com. Retrieved 2022-07-24.
 IBM. "Thales Vormetric Data Security Platform" (PDF). IBM.
External links
Gary Kessler's list of file signatures
Online File Signature Database for Forensic Practitioners, a private compilation free to Law Enforcement
Man page for compress, uncompress, and zcat on SCO Open Server
Public Database of File Signatures[dead link]
Complete list of magic numbers with sample files
the original libmagic data files with thousands of entries as used by file (command)
vte
Computer files
Types	
Binary file / text fileData fileFile format List of file formatsFile signaturesMagic numberOpen file formatsProprietary file formatsMetafileSidecar fileSparse fileSwap fileSystem fileTemporary fileZero-byte file
Properties	
Filename 8.3 filenameLong filenameFilename manglingFilename extension List of filename extensionsFile attribute Extended file attributesFile sizeHidden file / Hidden directory
Organisation	
Directory/folder NTFS linksTemporary folderDirectory structureFile system Filesystem Hierarchy StandardGrid file systemSemantic file systemPath
Operations	
OpenCloseReadWrite
Linking	
File descriptorHard linkShortcut AliasShadowSymbolic link
Management	
BackupFile comparisonFile copyingData compressionFile manager Comparison of file managersFile system fragmentationFile-system permissionsFile transfer File sharingFile synchronizationFile verification
Categories: Computer file formatsComputing-related lists
This page was last edited on 28 May 2024, at 02:58 (UTC).
Text is available under the Creative Commons Attribution-ShareAlike License 4.0; additional terms may apply. By using this site, you agree to the Terms of Use and Privacy Policy. Wikipedia® is a registered trademark of the Wikimedia Foundation, Inc., a non-profit organization.
Privacy policyAbout WikipediaDisclaimersContact WikipediaCode of ConductDevelopersStatisticsCookie statementMobile viewWikimedia FoundationPowered by MediaWiki
Toggle limited content width


#%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

GCK'S FILE SIGNATURES TABLE
Page last updated: Sat 30 March 2024 14:12:24 UTC

This table of file signatures (aka "magic numbers") is a continuing work-in-progress. I had found little information on this in a single place, with the exception of the table in Forensic Computing: A Practitioner's Guide by T. Sammes & B. Jenkinson (Springer, 2000); that was my inspiration to start this list in 2002. See also Wikipedia's List of file signatures. Comments, additions, and queries can be sent to Gary Kessler at gck@garykessler.net.

This list is not exhaustive although I add new files as I find them or someone contributes signatures. Interpret the table as a one-way function: the magic number generally indicates the file type whereas the file type does not always have the given magic number. If you want to know to what a particular file extension refers, check out File Extension Seeker: Metasearch engine for file extensions.

Some other useful information:

My software utility page contains a custom signature file based upon this list, for use with FTK, Scalpel, Simple Carver, Simple Carver Lite, and TrID. There is also a raw CSV file and JSON file of signatures.

Tim Coakley's Filesig.co.uk site, with Filesig Manager and Simple Carver. Also, see Tim's SQLite Database Catalog page, "a repository of information used to identify specific SQLite databases and properties for research purposes."

Marco Pontello's TrID - File Identifier utility designed to identify file types from their binary signatures.

The National Archives' PRONOM site provides on-line information about data file formats and their supporting software products, as well as their multi-platform DROID (Digital Record Object Identification) software.

Additional details on graphics file formats can be found at The Graphics File Formats Page and the Sustainability of Digital Formats Planning for Library of Congress Collections site.

Additional details on audio and video file formats can be found at the Sustainability of Digital Formats Planning for Library of Congress Collections site.

If you are using a Linux/MacOS/Unix system, you can use the file command to determine the file type based upon the file signature, per the system's magic file.

And, one last and final item — if you are searching for network traffic in raw binary files (e.g., RAM or unallocated space), see Hints About Looking for Network Packet Fragments.

ACKNOWLEDGEMENTS & COPYRIGHT NOTICE

Hex Signature	   	           ASCII Signature
File Extension	 	           File Description

TGA	 	Truevision Targa Graphic file
Trailer:
54 52 55 45 56 49 53 49   TRUEVISI
4F 4E 2D 58 46 49 4C 45   ON-XFILE
2E 00                     ..

00	 	.
PIC	 	IBM Storyboard bitmap file
MOV	 	Apple QuickTime movie file
PIF	 	Windows Program Information File
SEA	 	Mac Stuffit Self-Extracting Archive
YTR	 	IRIS OCR data file

00 00 00	 	...
AVIF	 	Alliance for Open Media (AOMedia) Video 1 (AV1) Image File

00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00	 	........
........
XXX	 	Compucon/Singer embroidery design file

[11 byte offset]
00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00
00 00 00 00 00 00 00 00	 	[11 byte offset]
........
........
........
PDB	 	Palmpilot Database/Document File

[512 (0x200) byte offset]
00 00 00 00 00 00 00 00	 	[512 (0x200) byte offset]
........
RVT	 	Revit Project File subheader

00 00 00 00 14 00 00 00	 	........
TBI	 	Windows Disk Image file

[4 byte offset]
66 74 79 70 68 65 69 63	 	[4 byte offset]
ftypheic
HEIC	 	High Efficiency Image Container (HEIC), holding one or more High Efficiency Image File (HEIF)
— aka H.265 — images, created using the High Efficiency Video Coding (HEVC) algorithm.
Developed by the Moving Pictures Experts Group (MPEG) and adopted by Apple as the standard image
file format in 2017.

[8 byte offset]
00 00 00 00 62 31 05 00
09 00 00 00 00 20 00 00
00 09 00 00 00 00 00 00	 	[8 byte offset]
....b1..
..... ..
........
DAT	 	Bitcoin Core wallet.dat file

00 00 00 0C 6A 50 20 20
0D 0A	 	....jP
..
JP2	 	Various JPEG-2000 image file formats

00 00 01 00	 	....
ICO	 	Windows icon file
SPL	 	Windows NT/2000/XP printer spool file

00 00 01 Bx	 	....
MPEG, MPG	 	MPEG video file
Trailer:
00 00 01 B7 (...·)

00 00 01 BA	 	....º
MPG, VOB	 	DVD Video Movie File (video/dvd, video/mpeg) or DVD MPEG2
Trailer:
00 00 01 B9 (...¹)

00 00 02 00	 	......
CUR	 	Windows cursor file
WB2	 	QuattroPro for Windows Spreadsheet file

00 00 02 00 06 04 06 00
08 00 00 00 00 00	 	........
......
WK1	 	Lotus 1-2-3 spreadsheet (v1) file

00 00 03 F3	 	...ó
n/a	 	Amiga Hunk executable file

00 00 1A 00 00 10 04 00
00 00 00 00	 	........
....
WK3	 	Lotus 1-2-3 spreadsheet (v3) file

00 00 1A 00 02 10 04 00
00 00 00 00	 	........
....
WK4, WK5	 	Lotus 1-2-3 spreadsheet (v4, v5) file

00 00 1A 00 05 10 04	 	.......
123	 	Lotus 1-2-3 spreadsheet (v9) file

00 00 49 49 58 50 52 or	 	..IIXPR
00 00 4D 4D 58 50 52	 	..MMXPR
QXD	 	Quark Express document (Intel & Motorola, respectively)
NOTE: It appears that the byte following the 0x52 ("R") is
the language indicator; 0x33 ("3") seems to indicate English
and 0x61 ("a") reportedly indicates Korean.

00 00 FE FF	 	..þÿ
n/a	 	Byte-order mark for 32-bit Unicode Transformation Format/
4-octet Universal Character Set (UTF-32/UCS-4), big-endian files.
(See the Unicode Home Page.)

[6 byte offset]
00 00 FF FF FF FF	 	[6 byte offset]
..ÿÿÿÿ
HLP	 	Windows Help file

00 01 00 00 00	 	.....
TTF	 	TrueType font file

00 01 00 00 4D 53 49 53
41 4D 20 44 61 74 61 62
61 73 65	 	....MSIS
AM Datab
ase
MNY	 	Microsoft Money file

00 01 00 00 53 74 61 6E
64 61 72 64 20 41 43 45
20 44 42	 	....Stan
dard ACE
 DB
ACCDB	 	Microsoft Access 2007 file

00 01 00 00 53 74 61 6E
64 61 72 64 20 4A 65 74
20 44 42	 	....Stan
dard Jet
 DB
MDB	 	Microsoft Access file

00 01 00 08 00 01 00 01
01	 	........
.
IMG	 	Ventura Publisher/GEM VDI Image Format Bitmap file

00 01 01	 	...
FLT	 	OpenFlight 3D file

00 01 42 41	 	..BA
ABA	 	Palm Address Book Archive file

00 01 42 44	 	..BD
DBA	 	Palm DateBook Archive file

00 06 15 61 00 00 00 02
00 00 04 D2 00 00 10 00	 	...a....
...Ò....
DB	 	Netscape Navigator (v4) database file

00 0D BB A0	 	..» 
n/a	 	Mbox table of contents file. (NOTE: The next four bytes
appear to be the number of e-mails in the associated mbox file.)

00 11 AF	 	..¯
FLI	 	FLIC Animation file

00 14 00 00 01 02 xx xx
03	 	........
.
n/a	 	BIOS details in RAM images

00 1E 84 90 00 00 00 00	 	..„.....
SNM	 	Netscape Communicator (v4) mail folder

00 20 AF 30	 	. ¯0
TPL	 	Wii images container

00 3B 05 00 01 00 00 00	 	.;......
DB	 	Paessler PRTG Monitoring System database file

00 5C 41 B1 FF	 	.\A±ÿ
ENC	 	Mujahideen Secrets 2 encrypted file

[512 (0x200) byte offset]
00 6E 1E F0	 	[512 (0x200) byte offset]
.n.ð
PPT	 	PowerPoint presentation subheader (MS Office)

00 BF	 	.¿
SOL	 	Adobe Flash shared object file (e.g., Flash cookies)

00 FF FF FF FF FF FF FF
FF FF FF 00 00 02 00 01	 	.ÿÿÿÿÿÿÿ
ÿÿÿ.....
MDF	 	Alcohol 120% CD image

01 00 00 00	 	....
EMF	 	Extended (Enhanced) Windows Metafile Format, printer spool file
(0x18-17 & 0xC4-36 is Win2K/NT; 0x5C0-1 is WinXP)

01 00 00 00 01	 	.....
PIC	 	Unknown type picture file

01 00 09 00 00 03	 	......
WMF	 	Windows Metadata file (Win 3.x format)

01 00 02 00	 	....
ARF	 	Webex Advanced Recording Format files.

01 00 39 30	 	..90
FDB, GDB	 	Firebird and Interbase database files, respectively. See
IBPhoenix for more information.

01 01 47 19 A4 00 00 00
00 00 00 00	 	..G.#xA4...
....
TBI	 	The Bat! secure e-mail Message Base Index file

01 0F 00 00	 	....
MDF	 	Microsoft SQL Server 2000 database

01 10	 	..
TR1	 	Novell LANalyzer capture file

01 C0 0C	 	.À.
HED	 	HighEdit document

01 DA 01 01 00 03	 	.Ú....
RGB	 	Silicon Graphics RGB Bitmap

01 FF 02 04 03 02	 	.ÿ....
DRW	 	Micrografx vector graphic file

02 64 73 73	 	.dss
DSS	 	Digital Speech Standard (Olympus, Grundig, & Phillips), v2

03	 	.
DAT	 	MapInfo Native Data Format
DB3	 	dBASE III file

03 00 00 00	 	....
NFC	 	Nokia PC Suite Content Copier file
QPH	 	Quicken price history file

03 00 00 00 41 50 50 52	 	....APPR
ADX	 	Approach index file

03 64 73 73	 	.dss
DSS	 	Digital Speech Standard, v3

04	 	.
DB4	 	dBASE IV data file

04 00 00 00 xx xx xx xx
xx xx xx xx 20 03 00 00 or	 	........
.... ...
05 00 00 00 xx xx xx xx
xx xx xx xx 20 03 00 00	 	........
.... ...
n/a	 	INFO2 Windows recycle bin file. NOTE: Bytes 12-13
indicate the size of each INFO2 record; the most common
value is 0x20-03 (0x0320 = 800 bytes).

06 06 ED F5 D8 1D 46 E5
BD 31 EF E7 FE 74 B7 1D	 	..íõØ.Få
½1ïçþt·.
INDD	 	Adobe InDesign document

06 0E 2B 34 02 05 01 01
0D 01 02 01 01 02	 	..+4....
......
MXF	 	Material Exchange Format file

07	 	.
DRW	 	A common signature and file extension for many drawing
programs.

07 53 4B 46	 	.SKF
SKF	 	SkinCrafter skin file

07 64 74 32 64 64 74 64	 	.dt2ddtd
DTD	 	DesignTools 2D Design file

08	 	.
DB	 	dBASE IV or dBFast configuration file

08 00 45	 	..E
n/a	 	Possibly, maybe, might be a fragment of an Ethernet frame carrying
an IPv4 packet. See Hints About Looking for Network Packet Fragments.

[512 (0x200) byte offset]
09 08 10 00 00 06 05 00	 	[512 (0x200) byte offset]
........
XLS	 	Excel spreadsheet subheader (MS Office)

0A nn 01	 	...
PCX	 	ZSOFT Paintbrush file
(where Version (nn) = 0x00, 0x02, 0x03, 0x04, or 0x05)

0A 16 6F 72 67 2E 62 69
74 63 6F 69 6E 2E 70 72	 	..org.bi
tcoin.pr
WALLET	 	MultiBit Bitcoin wallet file

0C ED	 	.í
MP	 	Monochrome Picture TIFF bitmap file (unconfirmed)

0D 44 4F 43	 	.DOC
DOC	 	DeskMate Document file

0E 4E 65 72 6F 49 53 4F	 	.NeroISO
NRI	 	Nero CD Compilation

0E 57 4B 53	 	.WKS
WKS	 	DeskMate Worksheet

[512 (0x200) byte offset]
0F 00 E8 03	 	[512 (0x200) byte offset]
..è.
PPT	 	PowerPoint presentation subheader (MS Office)

0F 53 49 42 45 4C 49 55
53	 	.SIBELIU
S
SIB	 	Sibelius Music - Score file

10 00 00 00	 	....
CL5	 	Easy CD Creator 5 Layout file

1A 00 00	 	...
NTF	 	Lotus Notes database template

1A 00 00 04 00 00	 	......
NSF	 	Lotus Notes database

1A 0x	 	..
ARC	 	LH archive file, old version
(where x = 0x2, 0x3, 0x4, 0x8 or 0x9
for types 1-5, respectively)

1A 0B	 	..
PAK	 	Compressed archive file
(often associated with Quake Engine games)

1A 35 01 00	 	.5..
ETH	 	GN Nettest WinPharoah capture file

1A 45 DF A3	 	.Eß£
MKV	 	Matroska stream file
WEBM	 	WebM video file

1A 52 54 53 20 43 4F 4D
50 52 45 53 53 45 44 20
49 4D 41 47 45 20 56 31
2E 30 1A	 	.RTS COM
PRESSED
IMAGE V1
.0.
DAT	 	Runtime Software compressed disk image

1D 7D	 	.}
WS	 	WordStar Version 5.0/6.0 document

1F 8B 08	 	.‹.
GZ, TGZ	 	GZIP archive file
VLT	 	VLC Player Skin file

1F 8B 08 00	 	.‹..
DSS	 	Synology router configuration backup file

1F 9D	 	..
TAR.Z	 	Compressed tape archive file using standard (Lempel-Ziv-Welch) compression

1F A0	 	. 
TAR.Z	 	Compressed tape archive file using LZH (Lempel-Ziv-Huffman) compression

21	 	!
BSB	 	Pitney Bowes' MapInfo Sea Chart format

21 0D 0A 43 52 52 2F 54
68 69 73 20 65 6C 65 63
74 72 6F 6E 69 63 20 63
68 61 72 74 20 77 61 73
20 70 72 6F 64 75 63 65
64 20 75 6E 64 65 72 20
74 68 65 20 61 75 74 68
6F 72 69 74 79 20 6F 66
20 55 53 41 2D 4E 4F 41
41 2F 4E 4F 53 2E 0D 0A	 	!..CRR/T
his elec
tronic c
hart was
 produce
d under
the auth
ority of
 USA-NOA
A/NOS...
BSB	 	NOAA Raster Navigation Chart (RNC®) file (https://charts.noaa.gov/RNCs/RNCs.shtml).
See also the BSB/KAP File Format specification

21 12	 	!.
AIN	 	AIN Compressed Archive

21 3C 61 72 63 68 3E 0A	 	!<arch>.
LIB	 	Unix archiver (ar) files and Microsoft Program Library
Common Object File Format (COFF)

21 42 44 4E	 	!BDN
 	 	Microsoft Outlook Personal Folder Files (PFF):
OST	 	Microsoft Outlook Offline Storage Folder File
PAB	 	Microsoft Outlook Personal Address Book File
PST	 	Microsoft Outlook Personal Folder File

23 20	 	#
MSI	 	Cerius2 file

23 20 44 69 73 6B 20 44
65 73 63 72 69 70 74 6F	 	# Disk D
escripto
VMDK	 	VMware 4 Virtual Disk description file (split disk)

23 20 4D 69 63 72 6F 73
6F 66 74 20 44 65 76 65
6C 6F 70 65 72 20 53 74
75 64 69 6F	 	# Micros
oft Deve
loper St
udio
DSP	 	Microsoft Developer Studio project file

23 20 54 68 69 73 20 69
73 20 61 6E 20 4B 65 79	 	# This i
s an Key
ETA	 	Google Earth Keyhole Placemark file

23 21 41 4D 52	 	#!AMR
AMR	 	Adaptive Multi-Rate ACELP (Algebraic Code Excited Linear Prediction)
Codec, commonly audio format with GSM cell phones. (See RFC 4867.)

23 21 53 49 4C 4B 0A	 	#!SILK.
SIL	 	Audio compression format developed by Skype; also used by other applications.

23 3F 52 41 44 49 41 4E
43 45 0A	 	#?RADIAN
CE.
HDR	 	Radiance High Dynamic Range image file

23 40 7E 5E	 	#@~^
VBE	 	VBScript Encoded script

23 4E 42 46	 	#NBF
NBF	 	NVIDIA Scene Graph binary file

23 50 45 43 30 30 30 31
4C 41 3A	 	#PEC0001
LA:
PEC	 	Brother/Babylock/Bernina Home Embroidery file

23 50 45 53 30	 	#PES0
PES	 	Brother/Babylock/Bernina Home Embroidery file

24 46 4C 32 40 28 23 29
20 53 50 53 53 20 44 41
54 41 20 46 49 4C 45	 	$FL2@(#)
 SPSS DA
TA FILE
SAV	 	SPSS Statistics (née Statistical Package for the Social Sciences, then
Statistical Product and Service Solutions) data file

25 21 50 53 2D 41 64 6F
62 65 2D	 	%!PS-Ado
be-
PS	 	PostScript file

25 21 50 53 2D 41 64 6F
62 65 2D 33 2E 30 20 45
50 53 46 2D 33 20 30	 	%!PS-Ado
be-3.0 E
PSF-3.0
EPS	 	Adobe encapsulated PostScript file
(If this signature is not at the immediate
beginning of the file, it will occur early
in the file, commonly at byte offset 30 [0x1E])

25 50 44 46	 	%PDF
PDF, FDF, AI	 	Adobe Portable Document Format, Forms Document Format, and Illustrator graphics files
Trailers:
0A 25 25 45 4F 46 (.%%EOF)
0A 25 25 45 4F 46 0A (.%%EOF.)
0D 0A 25 25 45 4F 46 0D 0A (..%%EOF..)
0D 25 25 45 4F 46 0D (.%%EOF.)
NOTE: There may be multiple end-of-file marks within the
file. When carving, be sure to get the last one.

25 62 69 74 6D 61 70	 	%bitmap
FBM	 	Fuzzy bitmap (FBM) file

28 54 68 69 73 20 66 69
6C 65 20 6D 75 73 74 20
62 65 20 63 6F 6E 76 65
72 74 65 64 20 77 69 74
68 20 42 69 6E 48 65 78
20	 	(This fi
le must
be conve
rted wit
h BinHex
 
HQX	 	Macintosh BinHex 4 Compressed Archive

2A 2A 2A 20 20 49 6E 73
74 61 6C 6C 61 74 69 6F
6E 20 53 74 61 72 74 65
64 20	 	***  Ins
tallatio
n Starte
d
LOG	 	Symantec Wise Installer log file

[2 byte offset]
2D 6C 68	 	[2 byte offset]
-lh
LHA, LZH	 	Compressed archive file

2E 52 45 43	 	.REC
IVR	 	RealPlayer video file (V11 and later)

2E 52 4D 46	 	.RMF
RM, RMVB	 	RealMedia streaming media file

2E 52 4D 46 00 00 00 12
00	 	.RMF....
.
RA	 	RealAudio file

2E 72 61 FD 00	 	.raý.
RA	 	RealAudio streaming media file

2E 73 6E 64	 	.snd
AU	 	NeXT/Sun Microsystems µ-Law audio file

2F 2F 20 3C 21 2D 2D 20
3C 6D 64 62 3A 6D 6F 72
6B 3A 7A	 	// <!--
<mdb:mor
k:z
MSF	 	Thunderbird|Mozilla Mail Summary File

30	 	0
CAT	 	Microsoft security catalog file

30 00 00 00 4C 66 4C 65	 	0...LfLe
EVT	 	Windows Event Viewer file

30 20 48 45 41 44	 	0 HEAD
GED	 	GEnealogical Data COMmunication (GEDCOM) file

30 26 B2 75 8E 66 CF 11
A6 D9 00 AA 00 62 CE 6C	 	0&²u.fÏ.
¦Ù.ª.bÎl
ASF, WMA, WMV	 	Microsoft Windows Media Audio/Video File
(Advanced Systems Format)

30 31 4F 52 44 4E 41 4E
43 45 20 53 55 52 56 45
59 20 20 20 20 20 20 20	 	01ORDNAN
CE SURVE
Y       
NTF	 	National Transfer Format Map File

30 37 30 37 30 nn	 	07070.
n/a	 	Archive created with the cpio utility (where nn
values 0x37 ("7"), 0x31 ("1"), and 0x32 ("2") refer to the
standard ASCII format, new ASCII (aka SVR4) format, and CRC
format, respectively. (The swpackage(8) page has additional
information.) (Thanks to F. Webber for this....)

31 BE or	 	1¾
32 BE	 	2¾
WRI	 	Microsoft Write file

32 03 10 00 00 00 00 00
00 00 80 00 00 00 FF 00	 	2.......
......ÿ.
PCS	 	Pfaff Home Embroidery file

34 CD B2 A1	 	4Í²¡
n/a	 	Extended tcpdump (libpcap) capture file (Linux/Unix)

37 7A BC AF 27 1C	 	7z¼¯'.
7Z	 	7-Zip compressed file

37 E4 53 96 C9 DB D6 07	 	7äS–ÛÖ.
n/a	 	zisofs compression format, recognized by some Linux kernels. See the
zisofs: format specification page.

38 42 50 53	 	8BPS
PSD	 	Photoshop image file

3A 56 45 52 53 49 4F 4E	 	:VERSION
SLE	 	Surfplan kite project file

3C	 	<
ASX	 	Advanced Stream redirector file
XDR	 	BizTalk XML-Data Reduced Schema file
WSF	 	Windows Script Component

3C 21 64 6F 63 74 79 70	 	<!doctyp
DCI	 	AOL HTML mail file

3C 3F	 	<?
WSC	 	Windows Script Component

3C 3F 78 6D 6C 20 76 65
72 73 69 6F 6E 3D	 	<?xml ve
rsion=
MANIFEST	 	Windows Visual Stylesheet XML file

3C 3F 78 6D 6C 20 76 65
72 73 69 6F 6E 3D 22 31
2E 30 22 3F 3E	 	<?xml ve
rsion="1
.0"?>
XUL	 	XML User Interface Language file

3C 3F 78 6D 6C 20 76 65
72 73 69 6F 6E 3D 22 31
2E 30 22 3F 3E 0D 0A 3C
4D 4D 43 5F 43 6F 6E 73
6F 6C 65 46 69 6C 65 20
43 6F 6E 73 6F 6C 65 56
65 72 73 69 6F 6E 3D 22	 	<?xml ve
rsion="1
.0"?>..<
MMC_Cons
oleFile
ConsoleV
ersion="
MSC	 	Microsoft Management Console Snap-in Control file

3C 43 54 72 61 6E 73 54
69 6D 65 6C 69 6E 65 3E	 	<CTransT
imeline>
MXF	 	Picasa movie project file

3C 43 73 6F 75 6E 64 53
79 6E 74 68 65 73 69 7A	 	<CsoundS
ynthesiz
CSD	 	Csound music file

3C 4B 65 79 68 6F 6C 65 3E	 	<Keyhole>
ETA	 	Google Earth Keyhole Overlay file

3C 4D 61 6B 65 72 46 69
6C 65 20	 	<MakerFi
le
FM, MIF	 	Adobe FrameMaker file

3C 67 70 78 20 76 65 72
73 69 6F 6E 3D 22 31 2E
31	 	<gpx ver
sion="1.
1
GPX	 	GPS eXchange file (v1.1 schema)

[58 byte offset]
3C 6B 39 73 65 74 74 69
6E 67 73	 	[58 byte offset]
<k9setti
ngs
K9S	 	K-9 Mail settings file (Android e-mail app)

3C 7E 36 3C 5C 25 5F 30
67 53 71 68 3B	 	<~6<\%_0
gSqh;
B85	 	ASCII85 (aka BASE85) encoded file, sometimes used with PostScript and PDF.
Trailer: 7E 3E 0A (~>.)

[24 (0x18) byte offset]
3E 00 03 00 FE FF 09 00
06	 	[24 (0x18) byte offset]
>...þÿ..
.
WB3	 	Quatro Pro for Windows 7.0 Notebook file

3F 5F 03 00	 	?_..
GID	 	Windows Help index file
HLP	 	Windows Help file

[32 (0x20) byte offset]
40 40 40 20 00 00 40 40
40 40	 	[32 (0x20) byte offset]
@@@ ..@@
@@
ENL	 	EndNote Library File

41 42 6F 78	 	ABox
ABOX2	 	Analog Box circuit files

41 43	 	AC
DWG	 	Generic AutoCAD drawing file

NOTES on AutoCAD file headers: The 0x41-43 (AC) is a generic header, occupying the first
two bytes in the file. The next three or four bytes give further indication about the version
(see also DWG file specifications released by OpenDesign):
0x31-2E-32 (1.2) — AutoCAD v1.2 (Release 2)
0x31-2E-33 (1.3) — AutoCAD v1.3 (Release 3)
0x31-2E-34-30 (1.40) — AutoCAD v1.40 (Release 4)
0x31-2E-35-30 (1.50) — AutoCAD v2.05 (Release 5)
0x32-2E-31-30 (2.10) — AutoCAD v2.10 (Release 6)
0x31-30-30-32 (1002) — AutoCAD v2.5 (Release 7)
0x31-30-30-33 (1003) — AutoCAD v2.6 (Release 8)
0x31-30-30-34 (1004) — AutoCAD v9.0 (Release 9)
0x31-30-30-36 (1006) — AutoCAD v10.0 (Release 10)
0x31-30-30-39 (1009) — AutoCAD v11.0 (Release 11)/v12.0 (Release 12)
0x31-30-31-32 (1012) — AutoCAD v13.0 (Release 13)
0x31-30-31-34 (1014) — AutoCAD v14.0 (Release 14)
0x31-30-31-35 (1015) — AutoCAD 2000 (v15.0)/2000i (v15.1)/2002 (v15.2) -- (Releases 15-17)
0x31-30-31-38 (1018) — AutoCAD 2004 (v16.0)/2005 (v16.1)/2006 (v16.2) -- (Releases 18-20)
0x31-30-32-31 (1021) — AutoCAD 2007 (v17.0)/2008 (v17.1)/2009 (v17.2) -- (Releases 21-23)
0x31-30-32-34 (1024) — AutoCAD 2010 (v18.0)/2011 (v18.1)/2012 (v18.2) -- (Releases 24-26)
0x31-30-32-37 (1027) — AutoCAD 2013 (v19.0)/2014 (v19.1)/2015 (v20.0)/2016 (v20.1)/2017 (v20.2) -- (Releases 27-31)
0x31-30-33-32 (1032) — AutoCAD 2018 (v22.0) (Release 32)
41 43 76	 	ACL
SLE	 	Steganos Security Suite virtual secure drive

41 43 53 44	 	ACSD
n/a	 	Miscellaneous AOL parameter and information files

41 45 53	 	AES
AES	 	AES Crypt file format. (The fourth byte is the version number, 0-2.)

41 4D 59 4F	 	AMYO
SYW	 	Harvard Graphics symbol graphic

41 4F 4C 20 46 65 65 64
62 61 67	 	AOL Feed
bag
BAG	 	AOL and AIM buddy list file

41 4F 4C 44 42	 	AOLDB
ABY, IDX	 	AOL database files: address book (ABY) and user configuration
data (MAIN.IDX)

41 4F 4C 49 44 58	 	AOLIDX
IND	 	AOL client preferences/settings file (MAIN.IND)

41 4F 4C 49 4E 44 45 58	 	AOLINDEX
ABI	 	AOL address book index file

41 4F 4C 56 4D 31 30 30	 	AOLVM100
ORG, PFC	 	AOL personal file cabinet (PFC) file
NOTE: See PFC-Details.zip for PFC file format information.

41 56 47 36 5F 49 6E 74
65 67 72 69 74 79 5F 44
61 74 61 62 61 73 65	 	AVG6_Int
egrity_D
atabase
DAT	 	AVG6 Integrity database file

41 72 43 01	 	ArC.
ARC	 	FreeArc compressed file

42 41 41 44	 	BAAD
n/a	 	NTFS Master File Table (MFT) entry (1,024 bytes)

42 44 69 63	 	BDic
BDIC	 	Google Chrome dictionary file

42 45 47 49 4E 3A 56 43
41 52 44 0D 0A	 	BEGIN:VC
ARD..
VCF	 	vCard file

42 4C 49 32 32 33	 	BLI223
BLI, RBI	 	Thomson Speedtouch series WLAN router firmware

NOTES on BLI/RBI file headers: The signature above is correct for the generic first six bytes.
Reportedly, the 7th & 8th bytes vary by version, and the 9th byte is always 0x30.
v6.0.7.1 (.bli) — 0x42-4C-49-32-32-33-51-4B-30 (BLI223QK0)
v7.4.1.7 (.bli) — 0x42-4C-49-32-32-33-51-48-30 (BLI223QH0)
v8.2.2.5 (.bli) — 0x42-4C-49-32-32-33-55-46-30 (BLI223UF0)
v8.4.3 (.bli/.rbi) — 0x42-4C-49-32-32-33-57-31-30 (BLI223W10)
42 4D	 	BM
BMP, DIB	 	Windows (or device-independent) bitmap image
NOTE: Bytes 2-5 contain the file length in little-endian order.

42 4F 4F 4B 4D 4F 42 49	 	BOOKMOBI
PRC	 	Palmpilot resource file

42 50 47 FB	 	BPG#xFB;
BPG	 	Better Portable Graphics image format

42 5A 68	 	BZh
BZ2, TAR.BZ2, TBZ2, TB2	 	bzip2 compressed archive
DMG	 	Mac Disk image (BZ2 compressed)

42 65 67 69 6E 20 50 75
66 66 65 72 20 44 61 74
61 0D 0A	 	Begin Pu
ffer Dat
a..
APUF	 	Puffer ASCII-armored encrypted archive

42 6C 69 6E 6B 20 62 79
20 44 2E 54 2E 53	 	Blink by
D.T.S
BLI	 	BLINK compressed archive

43 23 2B 44 A4 43 4D A5
48 64 72	 	C#+D¤CM¥
Hdr
RTD	 	RagTime document file

43 41 54 20	 	CAT
IFF	 	Electronic Arts' Interchange Format Files (IFF) format.

43 42 46 49 4C 45	 	CBFILE
CBD	 	WordPerfect dictionary file (unconfirmed)

43 44 30 30 31	 	CD001
ISO	 	ISO-9660 CD Disc Image
This signature usually occurs at byte offset 32769 (0x8001),
34817 (0x8801), or 36865 (0x9001).
More information can be found at MacTech or at ECMA.

43 49 53 4F	 	CISO
CSO	 	Compressed ISO (CISO) CD image

43 4D 4D 4D 15 00 00 00	 	CMMM....
DB	 	Windows 7 thumbcache_sr.db or other thumbcache file
(except thumbcache_idx.db)

43 4D 58 31	 	CMX1
CLB	 	Corel Binary metafile

43 4F 4D 2B	 	COM+
CLB	 	COM+ Catalog file

43 4F 57 44	 	COWD
VMDK	 	VMware 3 Virtual Disk (portion of a split disk) file

43 50 54 37 46 49 4C 45	 	CPT7FILE
CPT	 	Corel Photopaint file

43 50 54 46 49 4C 45	 	CPTFILE
CPT	 	Corel Photopaint file

43 52 45 47	 	CREG
DAT	 	Windows 9x registry hive

43 52 55 53 48 20 76	 	CRUSH v
CRU	 	Crush compressed archive

43 57 53	 	CWS
SWF	 	Macromedia Shockwave Flash player file (zlib compressed, SWF 6 and later).
See SWF File Format Specification.

43 61 6C 63 75 6C 75 78
20 49 6E 64 6F 6F 72 20	 	Calculux
Indoor
CIN	 	Calculux Indoor lighting design software project file

43 61 74 61 6C 6F 67 20
33 2E 30 30 00	 	Catalog
3.00.
CTF	 	WhereIsIt Catalog file

43 6C 69 65 6E 74 20 55
72 6C 43 61 63 68 65 20
4D 4D 46 20 56 65 72 20	 	Client U
rlCache
MMF Ver
DAT	 	Microsoft Internet Explorer cache file (index.dat) file

43 72 32 34	 	Cr24
CRX	 	Google Chrome Extension

43 72 4F 44	 	CrOD
CRX	 	Google Chromium patch update

43 72 65 61 74 69 76 65
20 56 6F 69 63 65 20 46	 	Creative
Voice F
VOC	 	Creative Voice audio file

44 41 41 00 00 00 00 00	 	DAA.....
DAA	 	PowerISO Direct-Access-Archive image

44 41 58 00	 	DAX.
DAX	 	DAX Compressed CD image

44 42 46 48	 	DBFH
DB	 	Palm Zire photo database

44 4D 53 21	 	DMS!
DMS	 	Amiga DiskMasher compressed archive

44 4F 53	 	DOS
ADF	 	Amiga disk file

44 53 44 20	 	DSD
DSF	 	DSD Storage Facility audio file

44 53 54 62	 	DSTb
DST	 	DST compressed file

44 56 44	 	DVD
DVR	 	DVR-Studio stream file
IFO	 	DVD info file

45 4C 49 54 45 20 43 6F
6D 6D 61 6E 64 65 72 20	 	ELITE Co
mmander
CDR	 	Elite Plus Commander saved game file

45 4E 54 52 59 56 43 44
02 00 00 01 02 00 18 58	 	ENTRYVCD
.......X
VCD	 	VideoVCD (GNU VCDImager) file

45 52 02 00 00	 	CD...
ISO	 	Apple ISO 9660/HFS hybrid CD image

45 52 46 53 53 41 56 45
44 41 54 41 46 49 4C 45	 	ERFSSAVE
DATAFILE
DAT	 	Kroll EasyRecovery Saved Recovery State file

45 50	 	EP
MDI	 	Microsoft Document Imaging file

45 56 46 09 0D 0A FF 00	 	EVF...ÿ.
Enn, Snn	 	Expert Witness Compression Format (EWF) file, including EWF-E01
and EWF-S01, as used in EnCase and SMART evidence files. Byte
offset 9 (i.e., byte #10) contains the segment number, starting with 0x01.
nn are the segment sequence number, taking on values 00..99, AA, AB...AZ, BA, BB...BZ, etc.
See the EWF specification.

45 56 46 32 0D 0A 81	 	EVF2...
Exnn	 	EnCase® Evidence File Format Version 2.
nn are the segment sequence number, taking on values 00..99, AA, AB...AZ, BA, BB...BZ, etc.
See the EWF 2 specification.

45 6C 66 46 69 6C 65 00	 	ElfFile.
EVTX	 	Windows Vista event log file

45 86 00 00 06 00	 	E†....
QBB	 	Intuit QuickBooks backup file

46 41 58 43 4F 56 45 52
2D 56 45 52	 	FAXCOVER
-VER
CPE	 	Microsoft Fax Cover Sheet

46 44 42 48 00	 	FDBH.
FDB	 	Fiasco database definition file

46 45 44 46	 	FEDF
SBV	 	(Unknown file type)

46 49 4C 45	 	FILE
n/a	 	NTFS Master File Table (MFT) entry (1,024 bytes)

46 4C 56 01	 	FLV.
FLV	 	Flash video file

46 4F 52 4D	 	FORM
ANM	 	IFF ANIM (Amiga delta/RLE encoded bitmap animation) file
IFF	 	Electronic Arts' Interchange Format Files (IFF) format.

46 4F 52 4D 00	 	FORM.
AIFF	 	Audio Interchange File
DAX	 	DAKX Compressed Audio

46 57 53	 	FWS
SWF	 	Macromedia Shockwave Flash player file (uncompressed). See
See SWF File Format Specification.

46 72 6F 6D 20 20 20 or	 	From
46 72 6F 6D 20 3F 3F 3F or	 	From ???
46 72 6F 6D 3A 20	 	From:
EML	 	A commmon file extension for e-mail files. Signatures shown here
are for Netscape, Eudora, and a generic signature, respectively.
EML is also used by Outlook Express and QuickMail.

47	 	G
TS, TSA, TSV	 	MPEG transport stream file. (This is not a lot to go on, but MPEG-2 Part 1
Transport (MP2T) files are reportedly broken into 188-byte packets and the
0x47 byte is the sync byte, so should repeat every 188 bytes in the file.)

47 46 31 50 41 54 43 48	 	GF1PATCH
PAT	 	Advanced Gravis Ultrasound patch file

47 49 46 38 37 61 or	 	GIF87a
47 49 46 38 39 61	 	GIF89a
GIF	 	Graphics interchange format file
Trailer: 00 3B (.;)

47 50 41 54	 	GPAT
PAT	 	GIMP (GNU Image Manipulation Program) pattern file

47 52 49 42	 	GRIB
GRB	 	GRIdded Binary or General Regularly-distributed Information in Binary file, commonly used in
meteorology to store historical and forecast weather data

47 58 32	 	GX2
GX2	 	Show Partner graphics file (not confirmed)

47 65 6E 65 74 65 63 20
4F 6D 6E 69 63 61 73 74	 	Genetec
Omnicast
G64	 	Genetec video archive

48 44 52 2A 50 6F 77 65
72 42 75 69 6C 64 65 72	 	HDR*Powe
rBuilder
PBD	 	SAP PowerBuilder integrated development environment file

48 45 41 44 45 52 20 52
45 43 4F 52 44 2A 2A 2A	 	HEADER R
ECORD***
XPT	 	SAS Transport dataset file format

48 48 47 42 31	 	HHGB1
SH3	 	Harvard Graphics presentation file

49 20 49	 	I I
TIF, TIFF	 	Tagged Image File Format file

49 44 33	 	ID3
MP3	 	MPEG-1 Audio Layer 3 (MP3) audio file

49 44 33 03 00 00 00	 	ID3....
KOZ	 	Sprint Music Store audio file (for mobile devices)

49 49 1A 00 00 00 48 45
41 50 43 43 44 52 02 00	 	II....HE
APCCDR..
CRW	 	Canon digital camera RAW file

49 49 2A 00	 	II*.
TIF, TIFF	 	Tagged Image File Format file (little
endian, i.e., LSB first in the byte; Intel)

49 49 2A 00 10 00 00 00
43 52	 	II*.....
CR
CR2	 	Canon digital camera RAW file

49 4D 4D 4D 15 00 00 00	 	IMMM....
DB	 	Windows 7 thumbcache_idx.db file

49 53 63 28	 	ISc(
CAB, HDR	 	Install Shield v5.x or 6.x compressed file

49 54 4F 4C 49 54 4C 53	 	ITOLITLS
LIT	 	Microsoft Reader eBook file

49 54 53 46	 	ITSF
CHI, CHM	 	Microsoft Compiled HTML Help File

49 6E 6E 6F 20 53 65 74
75 70 20 55 6E 69 6E 73
74 61 6C 6C 20 4C 6F 67
20 28 62 29	 	Inno Set
up Unins
tall Log
 (b)
DAT	 	Inno Setup Uninstall Log file

49 6E 74 65 72 40 63 74
69 76 65 20 50 61 67 65	 	Inter@ct
ive Page
IPD	 	Inter@ctive Pager Backup (BlackBerry) backup file

4A 41 52 43 53 00	 	JARCS.
JAR	 	JARCS compressed archive

4A 47 03 0E or	 	JG..
4A 47 04 0E	 	JG..
ART	 	AOL ART file
Trailers:
For 0x4A-47-03-0E: D0 CB 00 00 (ÐË..)
For 0x4A-47-04-0E: CF C7 CB (ÏÇË)

4B 44 4D	 	KDM
VMDK	 	VMware 4 Virtual Disk (portion of a split disk) file

4B 44 4D 56	 	KDMV
VMDK	 	VMware 4 Virtual Disk (monolitic disk) file

4B 47 42 5F 61 72 63 68
20 2D	 	KGB_arch
 -
KGB	 	KGB archive

4B 49 00 00	 	KI..
SHD	 	Windows 9x printer spool file

4B 57 41 4A 88 F0 27 D1	 	KWAJˆð'Ñ
n/a	 	KWAJ file format used by DOS COMPRESS.EXE and EXPAND.EXE commands.
This command compresses a single file, replacing the last character in the file name
with an underscore or dollar sign, e.g., FOO.BAZ would be renamed FOO.BA_ or
FOO.BA$. (See the SZDD/KWAJ page for more information.)

4C 00 00 00 01 14 02 00	 	L.......
LNK	 	Windows shell link (shortcut) file. See also The Meaning of Linkfiles in Forensic Examinations
and Evidentiary Value of Link Files.

4C 01	 	L.
OBJ	 	Microsoft Common Object File Format (COFF) relocatable
object code file for an Intel 386 or later/compatible processors

4C 41 3A	 	LA:
DST	 	Tajima embroidery sticj image file

4C 45 46 32 0D 0A 82 00	 	LEF2....
Lxnn	 	Logical File Evidence Format (EWF2-Lx01), used in Expert Witness Compression Format (EWF)
version 2 for Guidance Software Encase.
nn are the segment sequence number, taking on values 00..99, AA, AB...AZ, BA, BB...BZ, etc.
See the EWF2 specification.

4C 49 53 54	 	LIST
IFF	 	Electronic Arts' Interchange Format Files (IFF) format.

4C 4E 02 00	 	LN..
GID	 	Windows Help index file
HLP	 	Windows Help file

4C 50 46 20 00 01	 	LPF ..
ANM	 	DeluxePaint Animation file

4C 56 46 09 0D 0A FF 00	 	LVF...ÿ.
Lnn	 	Logical File Evidence Format (EWF-L01) as used in Expert Witness Compression Format (EWF)
for Guidance Software Encase. Byte offset 9 (i.e., byte #10) contains the segment number, starting with 0x01.
nn are the segment sequence number, taking on values 00..99, AA, AB...AZ, BA, BB...BZ, etc.
See the EWF specification.

4D 2D 57 20 50 6F 63 6B
65 74 20 44 69 63 74 69	 	M-W Pock
et Dicti
PDB	 	Merriam-Webster Pocket Dictionary file

4D 41 52 31 00	 	MAR1.
MAR	 	Mozilla archive

4D 41 52 43	 	MARC
MAR	 	Microsoft/MSN MARC archive

4D 41 54 4C 41 42 20 35
2E 30 20 4D 41 54 2D 66
69 6C 65	 	MATLAB 5
.0 MAT-f
ile
MAT	 	MATLAB v5 workspace file (includes creation timestamp)

4D 41 72 30 00	 	MAr0.
MAR	 	MAr compressed archive

4D 43 57 20 54 65 63 68
6E 6F 67 6F 6C 69 65 73	 	MCW Tech
nogolies
MTE	 	TargetExpress target file

4D 44 4D 50 93 A7	 	MDMP“§
HDMP	 	Windows heap dump file
DMP	 	Windows minidump file

4D 49 4C 45 53	 	MILES
MLS	 	Milestones v1.0 project management and scheduling software
(Also see "MV2C" and "MV214" signatures)

4D 4C 53 57	 	MLSW
MLS	 	Skype localization data file

4D 4D 00 2A	 	MM.*
TIF, TIFF	 	Tagged Image File Format file (big
endian, i.e., LSB last in the byte; Motorola)

4D 4D 00 2B	 	MM.+
TIF, TIFF	 	BigTIFF files; Tagged Image File Format files >4 GB

4D 4D 4D 44 00 00	 	MMMD..
MMF	 	Yamaha Corp. Synthetic music Mobile Application Format (SMAF)
for multimedia files that can be played on hand-held devices.

4D 52 56 4E	 	MRVN
NVRAM	 	VMware BIOS (non-volatile RAM) state file

4D 53 43 46	 	MSCF
CAB	 	Microsoft cabinet file
ONEPKG	 	OneNote Package file
PPZ	 	Powerpoint Packaged Presentation
SNP	 	Microsoft Access Snapshot Viewer file

4D 53 46 54 02 00 01 00	 	MSFT....
TLB	 	OLE, SPSS, or Visual C++ type library file

4D 53 48 7C 5E 7E 5C 26
7C	 	MSH|^~\&
|
HL7	 	Health Level-7 data (pipe delimited) file

4D 53 57 49 4D	 	MSWIM
WIM	 	Microsoft Windows Imaging Format file

4D 53 5F 56 4F 49 43 45	 	MS_VOICE
CDR, DVF	 	Sony Compressed Voice File
MSV	 	Sony Memory Stick Compressed Voice file

4D 54 68 64	 	MThd
MID, MIDI	 	Musical Instrument Digital Interface (MIDI) sound file
PCS	 	Yamaha Piano sound file

4D 56	 	MV
DSN	 	CD Stomper Pro label file

4D 56 32 31 34	 	MV214
MLS	 	Milestones v2.1b project management and scheduling software
(Also see "MILES" and "MV2C" signatures)

4D 56 32 43	 	MV2C
MLS	 	Milestones v2.1a project management and scheduling software
(Also see "MILES" and "MV214" signatures)

4D 5A	 	MZ
COM, DLL, DRV, EXE, PIF, QTS, QTX, SYS	 	Windows/DOS executable file
(See The MZ EXE File Format page for the structure of an EXE file,
with coverage of NE, TLINK, PE, self-extracting archives, and more.)
Note: MZ are the initals of Mark Zbikowski, designer of the DOS executable file format.
ACM	 	MS audio compression manager driver
AX	 	Library cache file
CPL	 	Control panel application
FON	 	Font file
OCX	 	ActiveX or OLE Custom Control
OLB	 	OLE object library
SCR	 	Screen saver
VBX	 	VisualBASIC application
VXD, 386	 	Windows virtual device drivers

4D 5A 90 00 03 00 00 00	 	MZ......
API	 	Acrobat plug-in
AX	 	DirectShow filter
FLT	 	Audition graphic filter file (Adobe)

4D 5A 90 00 03 00 00 00
04 00 00 00 FF FF	 	MZ......
....ÿÿ
ZAP	 	ZoneAlam data file

4D 69 63 72 6F 73 6F 66
74 20 43 2F 43 2B 2B 20	 	Microsof
t C/C++
PDB	 	Microsoft C++ debugging symbols file

4D 69 63 72 6F 73 6F 66
74 20 56 69 73 75 61 6C
20 53 74 75 64 69 6F 20
53 6F 6C 75 74 69 6F 6E
20 46 69 6C 65	 	Microsof
t Visual
 Studio
Solution
 File
SLN	 	Visual Studio .NET Solution file

[84 (0x54) byte offset]
4D 69 63 72 6F 73 6F 66
74 20 57 69 6E 64 6F 77
73 20 4D 65 64 69 61 20
50 6C 61 79 65 72 20 2D
2D 20	 	[84 (0x54) byte offset]
Microsof
t Window
s Media
Player -
-
WPL	 	Windows Media Player playlist

4D 73 52 63 66	 	MsRcf
GDB	 	VMapSource GPS Waypoint Database

4E 41 56 54 52 41 46 46
49 43	 	NAVTRAFF
IC
DAT	 	TomTom traffic data file

4E 42 2A 00	 	NB*.
JNT, JTP	 	MS Windows journal file

4E 45 53 4D 1A 01	 	NESM..
NSF	 	NES Sound file

4E 49 54 46 30	 	NITF0
NTF	 	National Imagery Transmission Format (NITF) file

4E 61 6D 65 3A 20	 	Name:
COD	 	Agent newsreader character map file

4F 50 43 4C 44 41 54	 	OPCLDAT
attachment	 	1Password 4 Cloud Keychain encrypted attachment

4F 50 4C 44 61 74 61 62
61 73 65 46 69 6C 65	 	OPLDatab
aseFile
DBF	 	Psion Series 3 Database file

4F 54 54 4F 00	 	OTTO.
OTF	 	OpenType font file

4F 67 67 53 00 02 00 00
00 00 00 00 00 00	 	OggS....
......
OGA, OGG, OGV, OGX	 	Ogg Vorbis Codec compressed Multimedia file

4F 7B	 	O{
DW4	 	Visio/DisplayWrite 4 text file (unconfirmed)

50 00 00 00 20 00 00 00	 	P... ...
IDX	 	Quicken QuickFinder Information File

50 35 0A	 	P5.
PGM	 	Portable Graymap Graphic

50 41 43 4B	 	PACK
PAK	 	Quake archive file

50 41 47 45 44 55 36 34	 	PAGEDU64
DMP	 	Windows 64-bit memory dump

50 41 47 45 44 55 4D 50	 	PAGEDUMP
DMP	 	Windows memory dump

50 41 58	 	PAX
PAX	 	PAX password protected bitmap

50 44 4E 33	 	PDN3
PDN	 	Paint.NET image (v3)

50 45 53 54	 	PEST
DAT	 	PestPatrol data/scan strings

50 47 50 64 4D 41 49 4E	 	PGPdMAIN
PGD	 	PGP disk image

50 49 43 54 00 08	 	PICT..
IMG	 	ADEX Corp. ChromaGraph Graphics Card Bitmap Graphic file

50 4B 03 04	 	PK..
ZIP	 	PKZIP archive file (Ref. 1 | Ref. 2)
Trailer: filename 50 4B 17 characters 00 00 00
Trailer: (filename PK 17 characters ...)
Note: PK are the initals of Phil Katz, co-creator of the ZIP file format and author of PKZIP.
ZIP	 	Apple Mac OS X Dashboard Widget, Aston Shell theme, Oolite eXpansion Pack,
Opera Widget, Pivot Style Template, Rockbox Theme package, Simple Machines
Forums theme, SubEthaEdit Mode, Trillian zipped skin, Virtual Skipper skin
APK	 	Android package
JAR	 	Java archive; compressed file package for classes and data
KMZ	 	Google Earth saved working session file
KWD	 	KWord document
ODT, ODP, OTT	 	OpenDocument text document, presentation, and text document template, respectively.
OXPS	 	Microsoft Open XML paper specification file
SXC, SXD, SXI, SXW	 	OpenOffice spreadsheet (Calc), drawing (Draw), presentation (Impress),
and word processing (Writer) files, respectively.
SXC	 	StarOffice spreadsheet
WMZ	 	Windows Media compressed skin file
XPI	 	Mozilla Browser Archive
XPS	 	XML paper specification file
XPT	 	eXact Packager Models

50 4B 03 04 0A 00 02 00	 	PK......
EPUB	 	Open Publication Structure eBook file. (Should also include the string:
mimetypeapplication/epub+zip)

50 4B 03 04 14 00 01 00
63 00 00 00 00 00	 	PK......
c.....
ZIP	 	ZLock Pro encrypted ZIP

50 4B 03 04 14 00 06 00	 	PK......
DOCX, PPTX, XLSX	 	Microsoft Office Open XML Format (OOXML) Document
NOTE: There is no subheader for MS OOXML files as there is with
DOC, PPT, and XLS files. To better understand the format of these files,
rename any OOXML file to have a .ZIP extension and then unZIP the file;
look at the resultant file named [Content_Types].xml to see the content
types. In particular, look for the <Override PartName= tag, where you
will find word, ppt, or xl, respectively.

Trailer: Look for 50 4B 05 06 (PK..) followed by 18 additional bytes
at the end of the file.

50 4B 03 04 14 00 08 00
08 00	 	PK......
..
JAR	 	Java archive

50 4B 05 06	 	PK..
ZIP	 	PKZIP empty archive file

50 4B 07 08	 	PK..
ZIP	 	PKZIP multivolume archive file

[30 (0x1E) byte offset]
50 4B 4C 49 54 45	 	[30 (0x1E) byte offset]
PKLITE
ZIP	 	PKLITE compressed ZIP archive (see also PKZIP)

[526 (0x20E) byte offset]
50 4B 53 70 58	 	[526 (0x20E) byte offset]
PKSFX
ZIP	 	PKSFX self-extracting executable compressed file (see also PKZIP)

50 4D 43 43	 	PMCC
GRP	 	Windows Program Manager group file

50 4E 43 49 55 4E 44 4F	 	PNCIUNDO
DAT	 	Norton Disk Doctor undo file

50 4D 4F 43 43 4D 4F 43	 	PMOCCMOC
DAT	 	Microsoft® Windows® User State Migration Tool (USMT). USMT 3.0
applies to Windows XP and Windows Vista®, and USMT 4.0 is for Windows 7.

50 53 46 12	 	PSF.
DSF	 	Dreamcast Sound Format file, a subset of the Portable Sound Format.

50 55 46 58	 	PUFX
PUF	 	Puffer encrypted archive

50 61 56 45	 	PaVE
n/a	 	Parrot Video Encapsulation file

[92 (0x5C) byte offset]
51 45 4C 20	 	[92 (0x5C) byte offset]
QEL
QEL	 	Quicken data file

51 46 49 FB	 	QFIû
IMG	 	QEMU Qcow Disk Image

51 57 20 56 65 72 2E 20	 	QW Ver.
ABD, QSD	 	Quicken data file

[512 (0x200) byte offset]
52 00 6F 00 6F 00 74 00
20 00 45 00 6E 00 74 00
72 00 79 00	 	[512 (0x200) byte offset]
R.o.o.t.
.E.n.t.
r.y.
MSG	 	Outlook/Exchange message subheader (MS Office)

52 41 5A 41 54 44 42 31	 	RAZATDB1
DAT	 	Shareaza (Windows P2P client) thumbnail

52 44 58 32 0A	 	RDX2.
RDATA	 	R (programming language) saved work space

52 45 47 45 44 49 54	 	REGEDIT
REG, SUD	 	Windows NT Registry and Registry Undo files

52 45 56 4E 55 4D 3A 2C	 	REVNUM:,
ADF	 	Antenna data file

52 49 46 46	 	RIFF
ANI	 	Windows animated cursor
CMX	 	Corel Presentation Exchange (Corel 10 CMX) Metafile
CDR	 	CorelDraw document
DAT	 	Video CD MPEG or MPEG1 movie file
DS4	 	Micrografx Designer v4 graphic file
4XM	 	4X Movie video

52 49 46 46 xx xx xx xx
41 56 49 20 4C 49 53 54	 	RIFF....
AVI LIST
AVI	 	Resource Interchange File Format -- Windows Audio Video
Interleave file, where xx xx xx xx is the file size (little endian)

52 49 46 46 xx xx xx xx
43 44 44 41 66 6D 74 20	 	RIFF....
CDDAfmt
CDA	 	Resource Interchange File Format -- Compact Disc Digital
Audio (CD-DA) file, where xx xx xx xx is the file size (little endian)

52 49 46 46 xx xx xx xx
51 4C 43 4D 66 6D 74 20	 	RIFF....
QLCMfmt
QCP	 	Resource Interchange File Format -- Qualcomm
PureVoice, where xx xx xx xx is the file size (little endian)

52 49 46 46 xx xx xx xx
52 4D 49 44 64 61 74 61	 	RIFF....
RMIDdata
RMI	 	Resource Interchange File Format -- Windows Musical
Instrument Digital Interface file, where xx xx xx xx is the file
size (little endian)

52 49 46 46 xx xx xx xx
57 41 56 45 66 6D 74 20	 	RIFF....
WAVEfmt
WAV	 	Resource Interchange File Format -- Audio for Windows
file, where xx xx xx xx is the file size (little endian)

52 49 46 46 xx xx xx xx
57 45 42 50	 	RIFF....
WEBP
WEBP	 	Google WebP image file, where xx xx xx xx is the file size

52 54 53 53	 	RTSS
CAP	 	Windows NT Netmon capture file

52 61 72 21 1A 07 00	 	Rar!...
RAR	 	RAR (v4.x) compressed archive file

52 61 72 21 1A 07 01 00	 	Rar!....
RAR	 	RAR (v5) compressed archive file

52 65 74 75 72 6E 2D 50
61 74 68 3A 20	 	Return-P
ath:
EML	 	A commmon file header for e-mail files.

[4 byte offset]
53 43 43 41	 	[4 byte offset]
SCCA
PF	 	Windows prefetch file. The first four bytes indicate the OS:
0x11-00-00-00 = XP, 0x17-00-00-00 = Vista/Win7,
and 0x1A-00-00-00 = Win8.1 (and probably Win8, as well).
See "Forensic Analysis of Prefetch files in Windows".

53 43 48 6C	 	SCHl
AST	 	Need for Speed: Underground Audio file

53 43 4D 49	 	SCMI
IMG	 	Img Software Set Bitmap

53 44 50 58	 	SDPX
DPX	 	Society of Motion Picture and Television Engineers (SMPTE)
Digital Picture Exchange (DPX) image file (big endian)

53 48 4F 57	 	SHOW
SHW	 	Harvard Graphics DOS Ver. 2/x Presentation file

53 49 45 54 52 4F 4E 49
43 53 20 58 52 44 20 53
43 41 4E	 	SIETRONI
CS XRD S
CAN
CPI	 	Sietronics CPI XRD document

53 49 4D 50 4C 45 20 20
3D 20 20 20 20 20 20 20
20 20 20 20 20 20 20 20
20 20 20 20 20 54	 	SIMPLE
=

     T
FITS	 	Flexible Image Transport System (FITS), Version 3.0 file

53 49 54 21 00	 	SIT!.
SIT	 	StuffIt compressed archive

53 4D 41 52 54 44 52 57	 	SMARTDRW
SDR	 	SmartDraw Drawing file

53 50 46 49 00	 	SPFI.
SPF	 	StorageCraft ShadownProtect backup file

53 50 56 42	 	SPVB
SPVCHAIN	 	MultiBit Bitcoin blockchain file

53 51 4C 4F 43 4F 4E 56
48 44 00 00 31 2E 30 00	 	SQLOCONV
HD..1.0.
CNV	 	DB2 conversion file

53 51 4C 69 74 65 20 66
6F 72 6D 61 74 20 33 00	 	SQLite f
ormat 3.
DB	 	SQLite database file

53 5A 20 88 F0 27 33 D1	 	SZ ˆð'3Ñ
n/a	 	QBASIC SZDD file header variant. (See the SZDD or KWAJ format entries
for additional information.)

53 5A 44 44 88 F0 27 33	 	SZDDˆð'3
n/a	 	SZDD file format used by DOS COMPRESS.EXE and EXPAND.EXE commands.
This command compresses a single file, replacing the last character in the file name
with an underscore or dollar sign, e.g., FOO.BAZ would be renamed FOO.BA_ or
FOO.BA$. (See the SZDD/KWAJ page for more information.)

53 6D 62 6C	 	Smbl
SYM	 	(Unconfirmed file type. Likely type is Harvard Graphics
Version 2.x graphic symbol or Windows SDK graphic symbol)

53 74 75 66 66 49 74 20
28 63 29 31 39 39 37 2D	 	StuffIt
(c)1997-
SIT	 	StuffIt compressed archive

53 75 70 65 72 43 61 6C
63	 	SuperCal
c
CAL	 	SuperCalc worksheet

54 48 50 00	 	THP.
THP	 	Wii/GameCube video file

54 68 69 73 20 69 73 20	 	This is
INFO	 	UNIX GNU Info Reader File

55 43 45 58	 	UCEX
UCE	 	Unicode extensions

55 46 41 C6 D2 C1	 	UFAÆÒÁ
UFA	 	UFA compressed archive

55 46 4F 4F 72 62 69 74	 	UFOOrbit
DAT	 	UFO Capture v2 map file

55 6E 46 69 6E 4D 46	 	UnFinMF
MF4	 	Unfinalized Measurement Data Format (MDF) file

56 43 50 43 48 30	 	VCPCH0
PCH	 	Visual C PreCompiled header file

56 45 52 53 49 4F 4E 20	 	VERSION
CTL	 	Visual Basic User-defined Control file

56 65 72 73 69 6F 6E 20	 	Version
MIF	 	MapInfo Interchange Format file

57 04 00 00 53 50 53 53
20 74 65 6D 70 6C 61 74	 	W...SPSS
templat
SCT	 	SPSS Statistics (née Statistical Package for the Social Sciences, then
Statistical Product and Service Solutions) template file

57 4D 4D 50	 	WMMP
DAT	 	Walkman MP3 container file

57 53 32 30 30 30	 	WS2000
WS2	 	WordStar for Windows Ver. 2 document

[29,152 (0x71E0) byte offset]
57 69 6E 5A 69 70	 	[29,152 (0x71E0) byte offset]
WinZip
ZIP	 	WinZip compressed archive

57 6F 72 64 50 72 6F	 	WordPro
LWP	 	Lotus WordPro document.

58 2D	 	X-
EML	 	A commmon file extension for e-mail files. This variant is
for Exchange.

58 43 50 00	 	XCP.
CAP	 	Cinco NetXRay, Network General Sniffer, and
Network Associates Sniffer capture file

58 50 43 4F 4D 0A 54 79
70 65 4C 69 62	 	XPCOM.Ty
peLib
XPT	 	XPCOM type libraries for the XPIDL compiler

58 50 44 53	 	XPDS
DPX	 	Society of Motion Picture and Television Engineers (SMPTE)
Digital Picture Exchange (DPX) image file (little endian)

58 54	 	XT..
BDR	 	MS Publisher border

5A 4F 4F 20	 	ZOO
ZOO	 	ZOO compressed archive

5A 57 53	 	ZWS
SWF	 	Macromedia Shockwave Flash player file (LZMA compressed, SWF 13 and later).
See SWF File Format Specification.

5B 47 65 6E 65 72 61 6C
5D 0D 0A 44 69 73 70 6C
61 79 20 4E 61 6D 65 3D
3C 44 69 73 70 6C 61 79
4E 61 6D 65	 	[General
]..Displ
ay Name=
<Display
Name
ECF	 	MS Exchange 2007 extended configuration file

5B 4D 53 56 43	 	[MSVC
VCW	 	Microsoft Visual C++ Workbench Information File

5B 50 68 6F 6E 65 5D	 	[Phone]
DUN	 	Dial-up networking file

5B 56 45 52 5D or	 	[VER]
5B 76 65 72 5D or	 	[ver]
SAM	 	Lotus AMI Pro document

5B 56 4D 44 5D or	 	[VMD]
VMD	 	VocalTec VoIP media file

[2 byte offset]
5B 56 65 72 73 69 6F 6E	 	[2 byte offset]
[Version
CIF	 	(Unknown file type)

5B 57 69 6E 64 6F 77 73
20 4C 61 74 69 6E 20	 	[Windows
 Latin
CPX	 	Microsoft Code Page Translation file

5B 66 6C 74 73 69 6D 2E
30 5D	 	[fltsim.
0]
CFG	 	Flight Simulator Aircraft Configuration file

5B 70 6C 61 79 6C 69 73
74 5D	 	[playlis
t]
PLS	 	WinAmp Playlist file

5D FC C8 00	 	]üÈ.
HUS	 	Husqvarna Designer I Embroidery Machine file

5F 27 A8 89	 	_'¨‰
JAR	 	Jar archive

5F 43 41 53 45 5F	 	_CASE_
CAS, CBK	 	EnCase case file (and backup)

60 EA	 	`ê
ARJ	 	Compressed archive file

62 65 67 69 6E	 	begin
n/a	 	UUencoded files start with a string:
  begin mode path
where mode is the set of permissions as used in
Linux/Unix and path is the name given to the decoded
file. (See this uuencode page for more information.)

62 65 67 69 6E 2D 62 61
73 65 36 34	 	begin-ba
se64
b64	 	UUencoded BASE64 file
Trailer: 0A 3D 3D 3D 3D 0A (.====.)

62 70 6C 69 73 74	 	bplist
plist	 	Binary property list (plist)
(NOTE: Next two bytes are the version number, currently
0x30-30, or "00")

63 61 66 66	 	caff
CAF	 	Apple Core Audio File

63 64 73 61 65 6E 63 72	 	cdsaencr
DMG	 	Macintosh encrypted Disk image (v1)

63 6F 6E 65 63 74 69 78	 	conectix
VHD	 	Virtual PC Virtual HD image footer

63 75 73 68 00 00 00 02
00 00 00	 	cush....
...
CSH	 	Photoshop Custom Shape

63 78 73 70 61 72 73 65	 	cxsparse
VHD	 	Virtual PC Virtual HD image dynamic disk header

64 00 00 00	 	d...
P10	 	Intel PROset/Wireless Profile

64 38 3A 61 6E 6E 6F 75
6E 63 65	 	d8:annou
nce
TORRENT	 	Torrent file

64 65 78 0A	 	dex.
dex	 	Dalvik executable file (Android)

64 6E 73 2E	 	dns.
AU	 	Audacity audio file

64 73 77 66 69 6C 65	 	dswfile
DSW	 	Microsoft Visual Studio workspace file

65 6E 63 72 63 64 73 61	 	encrcdsa
DMG	 	Macintosh encrypted Disk image (v2)

66 49 00 00	 	fI..
SHD	 	Windows NT printer spool file

66 4C 61 43 00 00 00 22	 	fLaC..."
FLAC	 	Free Lossless Audio Codec file

[4 byte offset]
66 74 79 70 33 67 70	 	[4 byte offset]
ftyp3gp
3GG, 3GP, 3G2	 	3rd Generation Partnership Project 3GPP multimedia files

[4 byte offset]
66 74 79 70 4D 34 41 20	 	[4 byte offset]
ftypM4A
M4A	 	Apple Lossless Audio Codec file

[4 byte offset]
66 74 79 70 4D 34 56 20	 	[4 byte offset]
ftypM4V
FLV, M4V	 	ISO Media, MPEG v4 system, or iTunes AVC-LC file

[4 byte offset]
66 74 79 70 4D 53 4E 56	 	[4 byte offset]
ftypMSNV
MP4	 	MPEG-4 video file

[4 byte offset]
66 74 79 70 69 73 6F 6D	 	[4 byte offset]
ftypisom
MP4	 	ISO Base Media file (MPEG-4) v1

[4 byte offset]
66 74 79 70 6D 70 34 32	 	[4 byte offset]
ftypmp42
M4V	 	MPEG-4 video|QuickTime file

[4 byte offset]
66 74 79 70 71 74 20 20	 	[4 byte offset]
ftypqt
MOV	 	QuickTime movie file

67 49 00 00	 	gI..
SHD	 	Windows 2000/XP printer spool file

67 69 6d 70 20 78 63 66
20	 	gimp xcf
XCF	 	GNU Image Manipulation Program (GIMP) eXperimental Computing Facility (XCF)
image file

68 49 00 00	 	hI..
SHD	 	Windows Server 2003 printer spool file

6B 87 08 38 76 C1 48 4E
B7 AE 04 04 6E 6C C7 52
01 00	 	h‡.8vÁHN
·®..nlÇR
..
VSC	 	Windows OS Volume Shadow Copy, index block header

69 63 6E 73	 	icns
ICNS	 	MacOS icon file

6C 33 33 6C	 	l33l
DBB	 	Skype user data file (profile and contacts)

[4 byte offset]
6D 6F 6F 76	 	[4 byte offset]
moov
MOV	 	QuickTime movie file

.MOV files have a complicated file signature. The string "moov" is the most common but I have also seen:
  0x66-72-65-65   free
  0x6D-64-61-74   mdat
  0x77-69-64-65   wide

And the following have been reported to me:
  0x70-6E-6F-74   pnot
  0x73-6B-69-70   skip

Furthermore, if you look at byte position xxxxxxxx+4 (where xxxxxxxx is bytes 0-3 of the header), you
will find one (or more!) of these strings repeated; the string "free" seems to be the most common. For
more information, see the QuickTime File Format page. (Thanks to D. Wright for getting me started on this!)

6D 73 46 69 6C 74 65 72
4C 69 73 74	 	msFilter
List
TPL	 	Internet Explorer v11 Tracking Protection List file

6D 75 6C 74 69 42 69 74
2E 69 6E 66 6F	 	multiBit
.info
INFO	 	MultiBit Bitcoin wallet information file

6F 3C	 	o<
n/a	 	Short Message Service (SMS), or text, message stored on a
Subscriber Identification Module (SIM).

6F 70 64 61 74 61 30 31	 	opdata01
n/a	 	1Password 4 Cloud Keychain encrypted data

72 65 67 66	 	regf
DAT	 	Windows NT registry hive file

72 69 66 66	 	riff
ACD	 	Sonic Foundry Acid Music File (Sony)

72 74 73 70 3A 2F 2F	 	rtsp://
RAM	 	RealMedia metafile

73 6C 68 21 or	 	slh!
DAT	 	Allegro Generic Packfile Data file (compressed)

73 6C 68 2E	 	slh.
DAT	 	Allegro Generic Packfile Data file (uncompressed)

73 6D 5F	 	sm_
PDB	 	PalmOS SuperMemo file

73 6F 6C 69 64	 	solid
STL	 	ASCII STL (STereoLithography) file for 3D printing.

73 72 63 64 6F 63 69 64
3A	 	srcdocid
:
CAL	 	CALS raster bitmap file

73 7A 65 7A	 	szez
PDB	 	PowerBASIC Debugger Symbols file

[60 (0x3C) byte offset]
74 42 4D 50 4B 6E 57 72	 	[60 (0x3C) byte offset]
tBMPKnWr
PRC	 	PathWay Map file, used with GPS devices

74 72 75 65 00	 	true.
TTF	 	TrueType font file

[257 (0x101) byte offset]
75 73 74 61 72	 	[257 (0x101) byte offset]
ustar
TAR	 	Tape Archive file (http://www.mkssoftware.com/docs/man4/tar.4.asp)

76 2F 31 01	 	v/1.
EXR	 	OpenEXR bitmap image format

76 32 30 30 33 2E 31 30
0D 0A 30 0D 0A	 	v2003.10
..0..
FLT	 	Qimage filter

77 4F 46 32	 	wOF2
WOFF2	 	Web Open Font Format 2

77 4F 46 46	 	wOFF
WOFF	 	Web Open Font Format

78 01 73 0D 62 62 60	 	x.s.bb`
DMG	 	Mac OS X Disk Copy Disk Image file

78 61 72 21	 	xar!
XAR	 	eXtensible ARchive file

7A 62 65 78	 	zbex
INFO	 	ZoomBrowser Image Index file (ZbThumbnal.info)

7B 0D 0A 6F 20	 	{..o
LGC, LGD	 	Windows application log

7B 22 75 72 6C 22 3A 20
22 68 74 74 70 73 3A 2F	 	{"url":
"https:/
GDOC	 	Google Drive Document link
GDRAW	 	Google Drive Drawing link

7B 44 52 4D 50 44 4B 7D	 	{DRMPDK}
....
DRMX, DRMZ	 	Drumlin Fully Secure PDF file. These files use a proprietary format that requires the Javelin PDF
Reader to be viewed and a unique authorization code. DRMZ files are compatible with mobile devices.

7B 5C 70 77 69	 	{\pwi
PWI	 	Microsoft Windows Mobile personal note file

7B 5C 72 74 66	 	{\rtf
RTF	 	Rich text format word processing file
Trailer: 7D (})

7C 4B C3 74 E1 C8 53 A4
79 B9 01 1D FC 4F DD 13	 	|KÃtáÈS¤
y¹..üOÝ.
CSD	 	Huskygram, Poem, or Singer embroidery design file

7E 42 4B 00	 	~BK.
PSP	 	Corel Paint Shop Pro image file

7E 45 53 44 77 F6 85 3E
BF 6A D2 11 45 61 73 79
20 53 74 72 65 65 74 20
44 72 61 77	 	~ESDwö…>
¿jÒ.Easy
 Street
Draw
ESD	 	Easy Street Draw diagram file

7E 74 2C 01 50 70 02 4D
52 01 00 00 00 08 00 00
00 01 00 00 31 00 00 00
31 00 00 00 43 01 FF 00
01 00 08 00 01 00 00 00
7e 74 2c 01	 	~t,.Pp.M
R.......
....1...
1...C.ÿ.
........
~t,.
IMG	 	Reportedly a proprietary recording system, possibly a
Digital Watchdog DW-TP-500G unit.

7F 45 4C 46	 	.ELF
n/a	 	Executable and Linking Format executable file (Linux/Unix)

80	 	.
OBJ	 	Relocatable object code

80 00	 	..
ADX	 	ADX lossy compressed audio file

80 2A 5F D7	 	.*_.
CIN	 	Kodak Cineon image file

81 32 84 C1 85 05 D0 11
B2 90 00 AA 00 3C F6 76	 	.2„Á….Ð.
²..ª.<öv
WAB	 	Outlook Express address book (Win95)

81 CD AB	 	.Í«
WPF	 	WordPerfect text file

86 DD 6x	 	†Ý{lower_case letter}
n/a	 	Possibly, maybe, might be a fragment of an Ethernet frame carrying
an IPv6 packet. See Hints About Looking for Network Packet Fragments.

89 50 4E 47 0D 0A 1A 0A	 	‰PNG....
PNG	 	Portable Network Graphics file
Trailer: 49 45 4E 44 AE 42 60 82 (IEND®B`‚...)

8A 01 09 00 00 00 E1 08
00 00 99 19	 	Š.....á.
..™.
AW	 	MS Answer Wizard file

91 33 48 46	 	‘3HF
HAP	 	Hamarsoft HAP 3.x compressed archive

95 00 or	 	•.
95 01	 	•.
SKR	 	PGP secret keyring file

97 4A 42 32 0D 0A 1A 0A	 	—JB2....
JB2	 	JBIG2 image file
Trailer: 03 33 00 01 00 00 00 00 (.3......)

99	 	™
GPG	 	GNU Privacy Guard (GPG) public keyring

99 01	 	™.
PKR	 	PGP public keyring file

9C CB CB 8D 13 75 D2 11
91 58 00 C0 4F 79 56 A4	 	œËË..UÒ.
‘X.ÀOyV¤
WAB	 	Outlook address file

[512 (0x200) byte offset]
A0 46 1D F0	 	[512 (0x200) byte offset]
 F.ð
PPT	 	PowerPoint presentation subheader (MS Office)

A1 B2 C3 D4	 	¡²ÃÔ
n/a	 	tcpdump (libpcap) capture file (Linux/Unix)

A1 B2 CD 34	 	¡²Í4
n/a	 	Extended tcpdump (libpcap) capture file (Linux/Unix)

A3 DE B0	 	£Þ°
HED	 	HighEdit document

A9 0D 00 00 00 00 00 00	 	©.......
DAT	 	Access Data FTK evidence file

AB 4B 54 58 20 31 31 BB
0D 0A 1A 0A	 	«KTX 11»
....
KTX	 	Khronos texture file for OpenGL and OpenGL ES applications

AC 9E BD 8F 00 00	 	¬.½...
QDF	 	Quicken data file

AC ED	 	¬í
n/a	 	Java serialization data (see Object Serialization Stream Protocol)

AC ED 00 05 73 72 00 12
62 67 62 6C 69 74 7A 2E	 	¬í..sr..
bgblitz.
PDB	 	BGBlitz (professional Backgammon software) position database file

B0 4D 46 43	 	°MFC
PWL	 	Windows 95 password file

B1 68 DE 3A	 	±hÞ:
DCX	 	Graphics Multipage PCX bitmap file

B4 6E 68 44	 	´nhd
TIB	 	Acronis True Image file (early versions)

B5 A2 B0 B3 B3 B0 A5 B5	 	µ¢°³³°¥µ
CAL	 	Windows calendar file

B8 C9 0C 00	 	¸É..
INS	 	InstallShield Script

BE 00 00 00 AB 00 00 00
00 00 00 00 00	 	¾...«...
....
WRI	 	MS Write file

BE BA FE CA 0F 50 61 6C
6D 53 47 20 44 61 74 61	 	¾ºþÊ.Pal
mSG Data
DAT	 	Palm Desktop DateBook file

C3 AB CD AB	 	Ã«Í«
ACS	 	MS Agent Character file

C5 D0 D3 C6	 	ÅÐÓÆ
EPS	 	Adobe encapsulated PostScript file

C8 00 79 00	 	È.y.
LBK	 	Jeppesen FliteLog file

CA FE BA BE	 	Êþº¾
CLASS	 	Java bytecode file (also used by Apple iOS apps)

CC 52 33 FC E9 2C 18 48
AF E3 36 30 1A 39 40 06	 	ÌR3üé,.H
¯ã60.9@.
NBU	 	Nokia phone backup file

CD 20 AA AA 02 00 00 00	 	Í ªª....
n/a	 	Norton Anti-Virus quarantined virus file

CE 24 B9 A2 20 00 00 00	 	Î$¹¢ ...
TIB	 	Acronis True Image file (current versions)

CE CE CE CE	 	ÎÎÎÎ
JCEKS	 	Java Cryptography Extension keystore file

CE FA ED FE	 	Îúíþ
n/a	 	Apple OS X ABI Mach-O binary file (32-bit, where target system has reverse byte
ordering from host running compiler)

CF 11 E0 A1 B1 1A E1 00	 	Ï.à¡±.á.
DOC	 	Perfect Office document
[Note similarity to MS Office header, below]

CF AD 12 FE	 	Ï­.þ
DBX	 	Outlook Express e-mail folder

CF FA ED FE	 	Ïúíþ
n/a	 	Apple OS X ABI Mach-O binary file (64-bit, where target system has reverse byte
ordering from host running compiler)

D0 CF 11 E0 A1 B1 1A E1	 	ÐÏ.à¡±.á
DOC, DOT, PPS, PPT, XLA, XLS, WIZ	 	An Object Linking and Embedding (OLE) Compound File (CF) (i.e., OLECF)
file format, known as Compound Binary File format by Microsoft, used by
Microsoft Office 97-2003 applications (Word, Powerpoint, Excel, Wizard). Part of
Microsoft's Structured Storage (MSS) architecture for Component Object Model (COM)-based
operating systems.
[See also Excel, Outlook, PowerPoint, and Word "subheaders" at byte offset 512 (0x200).]
There appear to several subheader formats and a dearth of documentation.
There have been reports that there are different subheaders for Windows and Mac
versions of MS Office but I cannot confirm that.]
Password-protected DOCX, XLSX, and PPTX files also use this signature those files
are saved as OLECF files.
[Note the similarity between D0 CF 11 E0 and the word "DOCFILE"!]
AC_	 	CaseWare Working Papers compressed client file
ADP	 	Access project file
APR	 	Lotus/IBM Approach 97 file
DB	 	MSWorks database file
MSC	 	Microsoft Common Console Document
MSG	 	Microsoft Outlook/Exchange Message
MSI	 	Microsoft Installer package
MSP	 	Windows Installer Patch
MTW	 	Minitab data file
MXD	 	ArcMap GIS project file
OPT	 	Developer Studio File Workspace Options file
PUB	 	MS Publisher file
QBM	 	QuickBooks Portable Company File
RVT	 	Revit Project file
SOU	 	Visual Studio Solution User Options file
SPO	 	SPSS output file
VSD	 	Visio file
WPS	 	MSWorks text document

D2 0A 00 00	 	Ò...
FTR	 	GN Nettest WinPharoah filter file

D4 2A	 	Ô*
ARL, AUT	 	AOL history (ARL) and typed URL (AUT) files

D4 C3 B2 A1	 	ÔÃ²¡
n/a	 	WinDump (winpcap) capture file (Windows)

D7 CD C6 9A	 	×ÍÆš
WMF	 	Windows graphics metafile

DB A5 2D 00	 	Û¥-.
DOC	 	Word 2.0 file

DC DC	 	ÜÜ
CPL	 	Corel color palette file

DC FE	 	Üþ
EFX	 	eFax file format

E3 10 00 01 00 00 00 00	 	ã.......
INFO	 	Amiga Icon file

E3 82 85 96	 	ã‚…–
PWL	 	Windows 98 password file

E4 52 5C 7B 8C D8 A7 4D
AE B1 53 78 D0 29 96 D3	 	äR\{ŒØ§M
®±SxÐ)–Ó
ONE	 	Microsoft OneNote note

E8 or	 	è
E9 or	 	é
EB	 	ë
COM, SYS	 	Windows executable file

EB 3C 90 2A	 	ë<.*
IMG	 	GEM Raster file

EB 52 90 2D 46 56 45 2D
46 53 2D	 	ëR.-FVE-
FS-
n/a	 	Header of boot sector in BitLocker protected volume (Vista)

EB 58 90 2D 46 56 45 2D
46 53 2D	 	ëX.-FVE-
FS-
n/a	 	Header of boot sector in BitLocker protected volume (Windows 7)

[512 (0x200) byte offset]
EC A5 C1 00	 	[512 (0x200) byte offset]
ì¥Á.
DOC	 	Word document subheader (MS Office)

ED AB EE DB	 	í«îÛ
RPM	 	RedHat Package Manager file

EF BB BF	 	ï»¿
n/a	 	Byte-order mark (BOM) for 8-bit Unicode Transformation Format
(UTF-8) files.
(See the Unicode Home Page.)

EF BB BF 3C	 	ï»¿<
WSF	 	Windows Script Component (UTF-8)

EF BB BF 3C 3F	 	ï»¿<?
WSC	 	Windows Script Component (UTF-8)

EF BB BF 3C 3F 78 6D 6C
20 76 65 72 73 69 6F 6E	 	ï»¿<?xml
 version
YTT	 	YouTube Timed Text (subtitle) file

[At a cluster boundary]
F0 FF FF	 	[At a cluster boundary]
ðÿÿ
n/a	 	FAT12 File Allocation Table

[At a cluster boundary]
F8 FF FF FF	 	[At a cluster boundary]
øÿÿÿ
n/a	 	FAT16 File Allocation Table

[At a cluster boundary]
F8 FF FF 0F FF FF FF 0F	 	[At a cluster boundary]
øÿÿ.ÿÿÿ.
n/a	 	FAT32 File Allocation Table

[At a cluster boundary]
F8 FF FF 0F FF FF FF FF	 	[At a cluster boundary]
øÿÿ.ÿÿÿÿ
n/a	 	FAT32 File Allocation Table

F9 BE B4 D9	 	ù¾´Ù
DAT	 	Bitcoin-Qt blockchain block file

FD 37 7A 58 5A 00	 	ý7zXZ.
XZ	 	XZ archive file

[512 (0x200) byte offset]
FD FF FF FF 02	 	[512 (0x200) byte offset]
ýÿÿÿ.
PUB	 	MS Publisher file subheader

[512 (0x200) byte offset]
FD FF FF FF 04	 	[512 (0x200) byte offset]
ýÿÿÿ.
MSG	 	Microsoft Outlook/Exchange Message
QBM	 	QuickBooks Portable Company File
SUO	 	Visual Studio Solution User Options subheader (MS Office)

[512 (0x200) byte offset]
FD FF FF FF nn nn 00 00	 	[512 (0x200) byte offset]
ýÿÿÿ....
PPT	 	PowerPoint presentation subheader (MS Office)

[512 (0x200) byte offset]
FD FF FF FF nn 00	 	[512 (0x200) byte offset]
ýÿÿÿ..
or
[512 (0x200) byte offset]
FD FF FF FF nn 02	 	[512 (0x200) byte offset]
ýÿÿÿ..
XLS	 	Excel spreadsheet subheader (MS Office)

[512 (0x200) byte offset]
FD FF FF FF 20 00 00 00	 	[512 (0x200) byte offset]
ýÿÿÿ ...
OPT	 	Developer Studio File Workspace Options subheader (MS Office)
XLS	 	Excel spreadsheet subheader (MS Office)

[512 (0x200) byte offset]
FD FF FF FF xx xx xx xx
xx xx xx xx 04 00 00 00	 	[512 (0x200) byte offset]
ýÿÿÿ....
........
DB	 	Thumbs.db subheader (MS Office)

FE ED FA CE	 	þíúÎ
n/a	 	Apple OS X ABI Mach-O binary file (32-bit)

FE ED FA CF	 	þíúÏ
n/a	 	Apple OS X ABI Mach-O binary file (64-bit)

FE ED FE ED	 	þíþí
JKS	 	JavaKeyStore file

FE EF	 	þï
GHO, GHS	 	Symantex Ghost image file

FE FF	 	þÿ
n/a	 	Byte-order mark (BOM) for 16-bit Unicode Transformation Format/
2-octet Universal Character Set (UTF-16/UCS-2), big-endian files.
(See the Unicode Home Page.)

FF	 	ÿ
SYS	 	Windows executable (SYS) file

FF 00 02 00 04 04 05 54
02 00	 	ÿ......T
..
WKS	 	Works for Windows spreadsheet file

FF 0A 00	 	ÿ..
QRP	 	QuickReport Report file

FF 46 4F 4E 54	 	ÿFONT
CPI	 	Windows international code page

FF 4B 45 59 42 20 20 20	 	ÿKEYB
SYS	 	Keyboard driver file

FF 57 50 43	 	ÿWPC
WP, WPD, WPG, WPP, WP5, WP6	 	WordPerfect text and graphics file

FF D8	 	ÿØ
JPE, JPEG, JPG	 	Generic JPEG Image file
Trailer: FF D9 (ÿÙ)

NOTES on JPEG file headers: The proper JPEG header is the two-byte sequence, 0xFF-D8, aka Start of Image (SOI) marker.
JPEG files end with the two-byte sequence, 0xFF-D9, aka End of Image (EOI) marker.

Between the SOI and EOI, JPEG files are composed of segments. Segments start with a two-byte Segment Tag followed by a
two-byte Segment Length field and then a zero-terminated string identifier (i.e., a character string followed by a 0x00), as
shown below with the JFIF, Exif, and SPIFF segments.

Segment Tags of the form 0x-FF-Ex (where x = 0..F) are referred to as APP0-APP15, and contain application-specific information. The
most commonly seen APP segments at the beginning of a JPEG file are APP0 and APP1 although others are also seen. Some additional
tags are shown below:

0xFF-D8-FF-E0 — Standard JPEG/JFIF file, as shown below.
0xFF-D8-FF-E1 — Standard JPEG file with Exif metadata, as shown below.
0xFF-D8-FF-E2 — Canon Camera Image File Format (CIFF) JPEG file (formerly used by some EOS and Powershot cameras).
0xFF-D8-FF-E8 — Still Picture Interchange File Format (SPIFF), as shown below.
FF D8 FF E0 xx xx 4A 46
49 46 00	 	ÿØÿà..JF
IF.
JFIF, JPE, JPEG, JPG	 	JPEG/JFIF graphics file
Trailer: FF D9 (ÿÙ)

FF D8 FF E1 xx xx 45 78
69 66 00	 	ÿØÿá..Ex
if.
JPG	 	Digital camera JPG using Exchangeable Image File Format (EXIF)
Trailer: FF D9 (ÿÙ)
See "Using Extended File Information (EXIF) File Headers in Digital
Evidence Analysis" (P. Alvarez, IJDE, 2(3), Winter 2004) and
ExifTool Tag Names

FF D8 FF E8 xx xx 53 50
49 46 46 00	 	ÿØÿè..SP
IFF.
JPG	 	Still Picture Interchange File Format (SPIFF)
Trailer: FF D9 (ÿÙ)

FF Ex	 	ÿ.
FF Fx	 	ÿ.
MPEG, MPG, MP3	 	MPEG audio file frame synch pattern

FF F1	 	ÿñ
AAC	 	MPEG-4 Advanced Audio Coding (AAC) Low Complexity (LC) audio file

FF F9	 	ÿù
AAC	 	MPEG-2 Advanced Audio Coding (AAC) Low Complexity (LC) audio file

FF FE	 	ÿþ
REG	 	Windows Registry file
n/a	 	Byte-order mark (BOM) for 16-bit Unicode Transformation Format/
2-octet Universal Character Set (UTF-16/UCS-2), little-endian files.
(See the Unicode Home Page.)

FF FE 00 00	 	ÿþ..
n/a	 	Byte-order mark for 32-bit Unicode Transformation Format/
4-octet Universal Character Set (UTF-32/UCS-4), little-endian files.
(See the Unicode Home Page.)

FF FE 23 00 6C 00 69 00
6E 00 65 00 20 00 31 00	 	ÿþ#.l.i.
n.e. .1.
MOF	 	Windows MSinfo file

FF FF FF FF	 	ÿÿÿÿ
SYS	 	DOS system driver

ACKNOWLEDGEMENTS

The following individuals have given me updates or suggestions for this list over the years: Devon Ackerman, Nazim Aliyev, Justin Almanza, Marco Barbieri, Vladimir Benko, Arvin Bhatnagar, Jim Blackson, Keith Blackwell, Alex Boschma, Sam Brothers, David Burton, Alex Caithness, Erik Campeau, Björn Carlin, Tim Carver, Michael D Cavalier, Per Christensson, Oscar Choi, JMJ.Conseil, Jesse Cooper, Jesse Corwin, Mike Daniels, David DeBrota, Cornelis de Groot, Jeffrey Duggan, Tony Duncan, Jon Eldridge, Ehsan Elhampour, Jean-Pierre Fiset, Peter Almer Frederiksen, Tim Gardner, Mark Gonyea, Chris Griffith, Linda Grody, Andis Grosšteins, Paulo Guzmán, Rich Hanes, George Harpur, Brian High, Eric Huber, Alexander Hübert, John Hughes, Allan Jensen, Broadus Jones, Matthew Kelly, Axel Kesseler, Nick Khor, Shane King, Art Kocsis, Thiemo Kreuz, Bill Kuhns, Evgenii Kustov, Andreas Kyrmegalos, Glenn Larsson, Jeremy Lloyd, Anand Mani, Kevin Mansell, Nevena Marković, Davyd McColl, Par Osterberg Medina, Michal, Sergey Miklin, David Millard, Bruce Modick, Lee Nelson, Mart Oskamp, Dan P., Jorge Paulhiac, Carlo Politi, Seth Polley, Hedley Quintana, Anthony Rabon, Stanley Rainey, Cory Redfern, Bruce Robertson, Ben Roeder, Thomas Rösner, Gerd, Röthig, Gaurav Sehgal, Andy Seitz, Anli Shundi, Erik Siers, Philip Smith, Mike Sutton, Matthias Sweertvaegher, Tobiasz Światlowski, Frank Thornton, Erik van de Burgwal, Øyvind Walding, Jason Wallace, Daniel Walton, Franklin Webber, Bernd Wechner, Douglas White, Mike Wilkinson, Gavin Williams, Sean Wolfinger, David Wright, Yuna, and Shaul Zevin. I thank them and apologize if I have missed anyone.

I would like to give particular thanks to Danny Mares of Mares and Company, author of the MaresWare Suite (primarily for the "subheaders" for many of the file types here), and the people at X-Ways Forensics for their permission to incorporate their lists of file signatures.

Finally, Dr. Nicole Beebe from The University of Texas at San Antonio posted samples of more than 32 file types at the Digital Corpora, which I used for verification and additional signatures. These files were used to develop the Sceadan File Type Classifier. The file samples can be downloaded from the Digital Corpora website.

COPYRIGHT NOTICE

All information on this page © 2002-2024, Gary C. Kessler. Permission to use the material here is extended to any of this page's visitors, as long as appropriate attribution is provided and the information is not altered in any way without express written permission of the author.


