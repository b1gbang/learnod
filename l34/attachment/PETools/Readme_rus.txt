==========================================================================
PE Tools v1.5.400.2003 Xmas Edition (for WinAll), by NEOx
Copyright [c] 2003 Underground InformatioN Center
==========================================================================

����������:

1. �������� ���������
2. ����
3. ���������
4. ������������� ��������� ������
5. ����������
6. ������� ������
7. �������������

1. �������� ���������
-----------------------------------
�������������������   �������   ���   ������   �   PE/PE+(64bit)  �������.
���������� � ����:  �������� PE ������,  Task  Viewer,  �����������  Win32
PE ������, �������� �����������/���������� � ������ ������.

�������� ����������� ���������:
+ Task Viewer
  - ����� ���������
    - Dump Full
    - Dump Partial
    - Dump Region
  - ����������� ������ ����� .NET CLR ���������
  - �������������� ������ ������ "Anti Dump Protection"
  - ��������� ���������� ��������
  - ���������� ������ ��������
  - �������� �������� � PE Editor � PE Sniffer
  - Generic OEP Finder
  
+ PE Sniffer
  - ����������� ���� �����������/����������
  - ����������� ���������� ���� ��������
  - ����������� ������������ ����������
  
+ PE Rebuilder
  - ����������� PE �����
  - ��������� �������� ������ PE �����
  
+ PE Editor
  - �������������� DOS ���������
  - ��������� ������ ������� PE+(64bit)
  - ��������������� CRC
  - �������� � �������������� ������ �������/��������

��������: ������ ����� ����� �� LordPE (�� Yoda) - ��� �������  ����������,
����� ����, ��������� � LordPE ������ ����� ������� �� ���� ���������, ����
���� ������� ����� �� ����������������!


2. ����
-----------------------------------
- Task viewer
  - ������ ���� ��������
  - ���������� ���� ��������
  - ���� ����� ��������� ������������ ��������
  - ����������� ������ ����� .NET CLR ���������
  - �������������� ������ ������ "Anti Dump Protection"
  - ��������� ���������� ��������
  - ���������� ��������
  - �������� �������� � PE Editor
  - �������� ����� �������� � PE Editor
  - Generic OEP Finder

- PE Sniffer
  - ����������� ���� �����������/����������
  - ����������� ���������� ����� ��������
  - ����������� ������������ ����������

- PE Rebuilder
  - ����������� PE �����
  - ��������� �������� ������ PE �����

- PE Editor
  - �������������� DOS ���������
  - ��������� ������ ������� PE+(64bit)

  [ �������������� PE ���������]
    - ����� ����������
    - ��������������� CRC
    - ����� �������������
    - ��������������� SizeOfHeaders

  [ Section Table Editor ]
    - �������������� ������
      - ����� ������������� ������
    - DumpFixer
    - �������� ����� ������
    - �������� ������
    - ���������� ������ �� ����
    - �������� ������ � �����

  [ Directory Table Editor ]
    - Export Table viewer
      - �������� � �������������� ������� ��������
    - Import Table viewer
      - �������� � �������������� ������� �������
    - Resource Directory viewer
    - Relocation viewer
    - Tls Table Editor
      - �������������� ������� TLS
    - Debug Directory viewer
    - Bound Import viewer
    - Load Config Editor
      - �������������� Load Config Directory
 
  [ ��������� PE ������ ]
    - ��������� PE ��������� � ������ (������ Win32 PE)


3. ���������
-----------------------------------
[ General ]
 - Always on top                     - ������ ���� ����
 - Restore last directory on startup - ���������� � �������������� ��������� ����������
 - Restore last main window position - ���������� � �������������� �������� ����
 - Automatically check for updates   - �������������� �������� ���������� (������ ����)

 Drag'n Dropped files are... - ��� Drag'n Drop, ���� ����� �������� �,...
   - ...for the PE Editor      �������� PE ������
   - ...for the PE Rebuilder   PE Rebuilder
   - ...for the PE Sniffer     PE Sniffer

[ PE Rebuilder ]
 - Register Shell Extension                - � ����������� ���� �������, ����� ��������
                                             ����� - Rebuild PE
 - Dump fix            - ��������������� PE �����, ����� ����� �� ������
                         (���������� ��� ����������������� ����� ����� ����� �� ������)
 - Wipe Relocation     - �������� �������
   - ... in Dll        - ������� ������ �� Dll
 - Validate PE         - ��������������� ����������, ��� �����������������
                         ��������� ��� Win2k
 - Rebuild PE          - ����������� �����
   - ... save overlay  - ������� ����� ��������
                         (���������� ��� ����������� ������������� � SFX �������)
   - File Alignment    - ���������� File Alignment (�� ��������� 0x200)

 - Bind Imports        - ����������� ��������
 - Change ImageBase to - ��������� �������� ������ ����� (������ ��� ������� �������)

[ Task Viewer ]
 - Full Dump: paste header from disk       - �������� PE ��������� ������ � �����
 - Full Dump: paste import table from disk - �������� ������� ������� ������ � �����
 - Full Dump: fix header                   - ��������������� PE �����
 - Full Dump: Force RAW mode               - �������������� ����������� ����� ��������
                                             (����������� �����, ����� PE Tools ������)
 - Full Dump: rebuild image                - ����������� �����
 - Agreement required for terminations     - ������������� ���������� ������ ��������
 - Delete temp files                       - �������� ���������� �����, ����� ��������
                                             ����� � PE Editor
 - Display SoftICE status                  - ����������� ������� SoftICE

[ PE Editor ]
 - Register Shell Extension                - � ����������� ���� �������, ����� ��������
                                             ����� - Load into PE Editor.
 - Create backup copy (BAK-file)           - �������� ��������� ����� �����
 - Read Only                               - ��������� ��� ����� - ������ ��� ������
 - Section Table: autofix SizeOfImage      - �������������� ��������������� SizeOfImage
 - Optional Header: autofix Checksum       - �������������� ��������������� Checksum
 - Optional Header: autofix SizeOfHeaders  - �������������� ��������������� SizeOfHeaders

[ PE Sniffer ]
 - Register Shell Extension                - � ����������� ���� �������, ����� ��������
                                             ����� - Load into PE Sniffer

[ Break & Enter ]
 - Register Shell Extension                - � ����������� ���� �������, ����� ��������
                                             ����� - Break & Enter

4. ������������� ��������� ������
-----------------------------------
PETools.exe:

/PEEDITOR pefile.exe
�������� ����� � PE Editor.
����� ���������� ������ ���� ���������!

/PESNIFFER pefile.exe
�������� ����� � PE Sniffer.

/REBUILDPE pefile.exe
�������� ����� � Rebuild PE.

/BREAKENTER pefile.exe
�������� ����� � "Break & Enter".


5. ����������
-----------------------------------
 - ��������! �������������� PE+(64bit) ������ ��������� �� �������������.


6. ������� ������
-----------------------------------
 - v1.5.400.2003 Xmas Edition - [08.12.2003]
        + �������� Generic OEP Finder
        + � Section Editor �������� DumpFixer
        + ��������� ����� ��������� (Tnx: .Cryorb/dyn!o/DeMoNiX/Aster!x/FEUERRADER)
        + ������������� ��� PE Sniffer-a
        + ��������� ����������� ����������������� SizeOfHeaders
        + �������� ����� ������ - Recover UPX by Quantum
        + �������� ToolBar
        + ����� ������ ����������� � INI �����
        + ������� ����������� �������� ���������� � Sections Editor'e � Directory Editor'e
        + � SDK �������� ������� �������� �� MASM32/Delphi
        + ������ ������ � PE Tools ���������������� ������� ��� �������� �������� (SignMan)
        + ������ PE Tools �� ��������� ������������� IMAGE_DOS_HEADER, ���� 
          c������� �� IMAGE_OPTIONAL_HEADER ������ ������� IMAGE_DOS_HEADER
        - ����� ������ ������ ���������� (UUpdateSystem.dll)
        - MMF ������� ����������� ������
        - ��������� ������� ��� � File Location Calculator (Tnx: cyberbob)
        - ��������� ��� � Kill Section (from file)
        - ��������� ��������� ��� � ������� ���������
        - ���������� ���� � Task Viewer'e
        - ��������� ��� � Break & Enter
        - ��������� ��� �� �� �������� ��������� ����� �� �����������
        - ��������� ��� �� �� �������� ��������� �� �������� ��� Win95 (Tnx: Lepton)
        - ����������� ��������� �������� ��������� ������

 - v1.5.320.2003 - [27.08.2003]
        + ��������� ����� ��������� (Tnx: .Cryorb/BiDark/dyn!o/Mike/DeMoNiX/Volodya)
        + ������������� ��� PE Sniffer-a
        + � PE Sniffer ��������� ����� ������ ������������: ����������� � �������������
        - ���������� ��������� ������ �����
        + ����������� �������� ��������� ������ (Tnx: Volodya, SEH)
        - ���������� ������� ���� � (Tnx: cyberbob):
                 - Full Dump: force RAW mode
                 - Full Dump: rebuild image
                 - Full Dump: paste header from disk

 - v1.5.300.2003 - [31.07.2003]
        - ���������� �������� ������ ����� (Tnx: .Cryorb & BiDark)
        - ��������� ����� ������� ��� � PE Sniffer-�. PE Sniffer �� �������
          ��� WinXP
        + ��� PE Sniffer-a ��������� ���������
        + ��������� ��������� ����� �������� (Tnx: .Cryorb & BiDark)
        + ��������� ��� ������ � ����������� ���� Section Editor-a:
                 - Kill Section (from header)
                 - Kill Section (from file)
                 - Fill Section
        + ��������� ����� ����� � Rebuild PE:
                 - File Alignment
        + ������ �������� ����� ������� �� ������� ������� Delete
        + �� ��� ������� ��������� ������ "X" :)

 - v1.5.220.2003 - [21.07.2003]
        + �������� ������ ��� �������������� �������
        + � ���� Task Viewer-� � PE Sniffer-a �������� ����� "Explorer..."
        - ��������� ������� ��� � PE Sniffer-�
        + ��������� ��������� ����� �������� �������
        - ��������� ��� � Debug Directory
        - � PE Editor-e ��������� ��� ����������� �������� ����� ����������

 - v1.5.110.2003 - [13.07.2003]
        - ��������� ���, ������� ������� ������ ��� ������ �� ��������� ��� WinXP

 - v1.5.109.2003 - [10.07.2003]
        + ��������� ����� ���������� ���������, Above Normal � Below Normal
          (������ ��� Win2k/XP)
        + ��������� ������ "?" ��� SizeOfImage
        + ��������� ����������� ������� SoftICE (Loaded/Not Loaded)
        + �������� File Location Calculator
        + ��������� ����������� �������������� Load Config Directory
        + ����������� �������� ��������� ������� ������� (Tnx: Volodya/WASM.RU)
        + ���������� ���� �������� ��� PE Sniffer-�, �� 339 �������� (Tnx: .Cryorb & BiDark)
        + PE Sniffer ������ ��������� ����������� ����������
        + ����� ����� � PE Sniffer-�:
                  - Directory Scan: Skip invalid PE files
                  - Directory Scan: Scan subfolders
        + ������� ������� ������ ���� �������� (Signs.txt)
        + ��������������� ��������� ������������� ��������
        + ��������� �������������� ���������:
                [ General ]
                  - Drag'n Dropped files are...for the PE Sniffer

                [ PE Sniffer ]
                  - Register Shell Extension

                [ Task Viewer ]
                  - Force RAW mode
                  - Display SoftICE status

                [ PE Rebuilder ]
                  - Register Shell Extension
        - ���������� ��������� ������������� ����
        - ���������� ���� � ������ ���������� (UUpdateSystem.dll)
        - ���������� ��������� ������ �����
        - ��������� ��� ��������� ��������� ������
        + ��������� ����� �������, ��� ������ � ���������� �� ��������� ������:
                  - "/PESNIFFER"
                  - "/REBUILDPE"

 - v1.4.419.2003 - [22.03.2003]
        - ���������� ��������� ������ �����
        + ������ ��������� ����� ������ ���������� ����� ��������� ����������
          tElock
        + ��������� ������� ���������� ����� ��������

 - v1.4.380.2003 - [08.03.2003]
        - ���������� ��������� ������ �����
        - Dump Region �� ������� � WinXP, ������ �������� :)
        + � PE Sniffer ��������� ����� 15 ����� ��������
        + � "Dump Region..." ��������� ������ "Refresh"
        + � "PE Rebuilder" ��������� Bind Imports
        + ��������� ����������� ���������� ������ ���������/������� �� ������� F5
        + ��������� ��������� ������ (���� ������ ��������� PE ���������)
        + �������� Time/Date Stamp Converter (GMT)
        + ��������� ��������� �������������� ��������:
                [ PE Editor ]
                  - Create backup copy (BAK-File)
                  - Read only
                  - Section Table: autofix SizeOfImage
                  - Optional Header: autofix Checksum
                  - Optional Header: autofix SizeOfHeaders

                [ PE Rebuilder ]
                  - Bind Imports

                [ Break & Enter ]
                  - Register Shell Extension

                [ Task Viewer ]
                  - Agreement required for terminations
                  - Delete temp files

        + ��������� ����������� �������� ����� �������� � PE Editor
        + ��������� ����������� �������� ����� �������� � PE PE Sniffer

 - v1.4.356.2003 Alpha - [28.01.2003]
        * ������ GUI �������� PE+(64bit) ������ � ���� :)
        - ��������� ��� �������������� �������� ����
        + ������ ��������� ��� �������� ������������� ������� ��� ����������
          �������, ����� ��� ProcDump/LordPE
        - ��������� ��� ���������� �������� ����
        + ��������� ��������� ���� ��� ���������
        + ��������� ��������� PE ������ ���������� � ����
          (������ ������������ Memory Mapped Files.)
        + ��������� �������� �� 95% �� ������ API. ������ ������ ���� � ���������� MFC
        - ��������� ��� ���� ��� ��� ��������� ������
          (���� ��� ������ ���� 8 ��������, ��������� �������� ��������� �������.)
        + ��������� ����� �����
        + ��������� ������� ��������
        + ��������� ����������� ������ ��������� ���������� ����� PE ���������
          (������ ��� ������������� ������ � ������������ �� PE �������, �����
           �������� �������� �������������� ������)
        + ��������� ��������� ������ PE+(64bit) �������
        + ��������� ��������� PE ������ (������ ��� PE �������)
        + ��������� ��������������� CRC �����
        + ��������� ��������������� SizeOfHeaders
        + ��������� �������������� ������� �������/��������
        + ��������� �������������� ������� TLS
        + �������� ������������ ��������
        + �������� ������������ Bound Import
        + �������� ������������ Debug Directory
        + �������� ������������ Relocation Table
        + �������� Task Viewer
        + �������� PE Tools Dumper Server
        + �������� PE Rebuilder (������ ��� PE32 �������)
        + �������� Break & Enter
        + �������� PE Sniffer
        + ��������� ������� ��������

 - v1.3 Build 60 - [09.12.2002]
        - ����� ���������� ���� ��� ������ � ��������

 - v1.3 Build 54 - [24.08.2002]
        + ������ ����� ������������� �������� ����� �������� ������
          (Full access ��� Read-Only)
        + ��������� ���������� � ����� ������ ��������� ����� �����.
        + �������� Drag-Drop
        + ��������� �������������� ������� ��� ������ � ��������.
        + ������� ��������� ��� ������ � PE �������
        - ���������� ���� ��� ������ � ��������

 - v1.3 - [01.06.2002]
        * ��������� ������������� � PE Tools (������� NiFi)
        + ������ ��������� ����� ������������� DOS-�����������
          ���������
        + ���������: �������� ��������� ����� � �������� 
          ������ ������ ��� ������
        + ����������� �������� ��������� ������������� PE-������
        - ��������� ��� �������� ������

 - v1.2 - [13.05.2002]
        - ���������� ��������� ����
        + ������ ��������� �� ��������� ����� Read-Only. ��� ��� ��� 
          �������� ������� ����
        + ��������� ������ ���������������� ������ � ����������
     
 - v1.1 - [07.05.2002]
        * ������ ��������� ������. GUI ����������
        - ��������� ���� � ��������
        + ��������� ���������� ������� ������ � PE �������
        + ������� �������������� � ���������� ���������
        + ������� ��������� ��������� ������
        + ��������� �������������� ���� ����������� � Advanced
          Information

 - v1.0 - [03.02.2002]
        * ����� ���� ���������� ������� � �� ����������������
        * ��� ���� ��� ������ � ��������, � ������ ������
        * ����� ���������� PE Editor

7. �������������
-----------------------------------
        NiFi/uinC           - �������, ���� � ������ ������...
        Corbio/uinC         - ������������ ��� Win2k
        SOLDIER/uinC        - ������������ ��� Win98
        Rook/uinC           - ��������� �� ����������
        Dr.Golova/uinC      - ������ � �������� Break & Enter �
			      PE Rebuilder-a
        SunteXx             - ������������ ��� WinXP
        http://www.geocities.com/winhider
        �������� �������    - ������������
        JFX                 - ������������
        dum0h               - ������������ ��� WinXP
        http://flashlib.kursknet.ru
        .Cryorb             - ������� ������� �� ������������� ����������
                              ���� ��������, PE Sniffer-�. � ��� �� �� ������������
        Volodya/WASM.RU     - �������, �� ����������, �������� ���� � �.�.
        http://www.wasm.ru
        BiDark              - ������� �� ����������, � ��������� ��������
        spEctoRius          - ������������ ��� WinXP
        http://www.spectorius.narod.ru/
        cyberbob            - ������������
        http://www.darmozjad.host.sk
        FEUERRADER          - ������������ ��� WinME, ������������� ��������� PE Tools
        http://www.feuerrader.tk
        .::D.e.M.o.M.i.X    - ��� �������, ���������
        http://reversing.kulichki.net
        dyn!o               - ��� �������, ���������, ����
        Bad_Guy             - ��� �������, ����
        http://cracklab.narod.ru
        Aster!x             - ��� �������, ����
        a_sterix_44_1@mail.ru
        lepton              - ������������ ��� Win95


��������� � ���������� ��������������! � ����������� ����� ����� ;)
� ���������, NEOx

=== by NEOx [E-Mail: NEOx@Pisem.net] =============== 08.12.03 ============
=== [c] Underground Information Center [ http://www.uinc.ru ] ============