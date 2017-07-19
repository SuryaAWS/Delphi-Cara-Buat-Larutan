unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, jpeg, ExtCtrls;

type
  TForm1 = class(TForm)
    StaticText1: TStaticText;
    GroupBox1: TGroupBox;
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    GroupBox2: TGroupBox;
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Edit1: TEdit;
    Edit2: TEdit;
    Edit3: TEdit;
    Edit4: TEdit;
    Edit5: TEdit;
    Label6: TLabel;
    Label7: TLabel;
    Label8: TLabel;
    Label9: TLabel;
    Label10: TLabel;
    Label11: TLabel;
    Label12: TLabel;
    Label13: TLabel;
    Label14: TLabel;
    Image1: TImage;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  mr,persen,rho,Mp,Me,Vp,Ve:real;

implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
begin
mr:=strtofloat(edit1.Text);
Ve:=strtofloat(edit2.Text);
Me:=strtofloat(edit3.Text);
persen:=strtofloat(edit4.Text);
rho:=strtofloat(edit5.Text);
Mp:=(rho*persen*1000)/(mr*100);
Vp:=(Ve*Me)/Mp;
label11.Caption:='sebesar '+floattostr(Vp)+' mL.';
label13.Caption:='Masukkan ke dalam labu takar '+floattostr(Ve)+' ml';
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
edit1.Text:='';
edit2.Text:='';
edit3.Text:='';
edit4.Text:='';
edit5.Text:='';
label11.Caption:='sebesar . . . mL.';
edit1.SetFocus;
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
close;
end;

end.
