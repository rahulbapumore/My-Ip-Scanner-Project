object Form1: TForm1
  Left = 487
  Top = 194
  Width = 594
  Height = 527
  Caption = 'IpScanner'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  OldCreateOrder = False
  OnCanResize = FormCanResize
  OnCreate = FormCreate
  PixelsPerInch = 96
  TextHeight = 13
  object FromIpLbl: TLabel
    Left = 52
    Top = 23
    Width = 110
    Height = 13
    Caption = 'Enter Start IP Address :'
  end
  object ToIpLbl: TLabel
    Left = 53
    Top = 60
    Width = 101
    Height = 13
    Caption = 'Enter End IP Address'
  end
  object NoOfThreadsLbl: TLabel
    Left = 53
    Top = 94
    Width = 130
    Height = 13
    Caption = 'Enter Number Of Threads  :'
  end
  object FromIpTxt: TEdit
    Left = 242
    Top = 20
    Width = 121
    Height = 21
    TabOrder = 0
    OnKeyPress = FromIpTxtKeyPress
    OnKeyUp = FromIpTxtKeyUp
  end
  object ToIpTxt: TEdit
    Left = 243
    Top = 56
    Width = 121
    Height = 21
    TabOrder = 1
    OnKeyPress = ToIpTxtKeyPress
    OnKeyUp = ToIpTxtKeyUp
  end
  object NoOfThreadsTxt: TEdit
    Left = 245
    Top = 88
    Width = 121
    Height = 21
    TabOrder = 2
    OnKeyPress = NoOfThreadsTxtKeyPress
    OnKeyUp = NoOfThreadsTxtKeyUp
  end
  object ScanBtn: TButton
    Left = 400
    Top = 112
    Width = 75
    Height = 25
    Caption = 'Scan'
    TabOrder = 3
    OnClick = ScanBtnClick
  end
  object StopBtn: TButton
    Left = 488
    Top = 112
    Width = 75
    Height = 25
    Caption = 'Stop'
    TabOrder = 4
  end
  object ListViewIp: TListView
    Left = 8
    Top = 144
    Width = 561
    Height = 337
    Columns = <
      item
        Caption = 'IP Address'
        Width = 275
      end
      item
        Caption = 'Host Name'
        Width = 282
      end>
    GridLines = True
    ReadOnly = True
    RowSelect = True
    ParentShowHint = False
    ShowHint = True
    TabOrder = 5
    ViewStyle = vsReport
  end
end
