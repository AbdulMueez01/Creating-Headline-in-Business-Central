pageextension 50101 "Olanrewaju" extends "Headline RC Business Manager"
{
    layout
    {
        addbefore(Control1)
        {
            field(HeadlineTxt; HeadlineTxt)
            {
                ApplicationArea = All;
            }
        }
    }
    trigger OnOpenPage()

    begin
        HeadlineTxt := 'Hello Olanrewaju Adesanya'
    end;

    var
        HeadlineTxt: Text;
