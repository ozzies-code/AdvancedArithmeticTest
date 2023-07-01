# AdvancedArithmeticTest
Advanced Arithmetic Test: Perform the calculation on a variable with Advanced operations of mathematics: Division of Integers, Remainder, Exponentiation and Concatenation.
Visual Basic 2005.NET:
Public Class Form1

    Private Sub Button1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles Button1.Click

        'Declara las variables PrimerNum y SegundoNum
        Dim PrimerNum, SegundoNum As String

        'Asigna los valores de los cuadros de texto a las variables
        PrimerNum = TextBox1.Text
        SegundoNum = TextBox2.Text

        'Determina que boton se activa y hace el calculo
        If RadioButton1.Checked = True Then
            TextBox3.Text = PrimerNum \ SegundoNum
        End If

        If RadioButton2.Checked = True Then
            TextBox3.Text = PrimerNum Mod SegundoNum
        End If

        If RadioButton3.Checked = True Then
            TextBox3.Text = PrimerNum ^ SegundoNum
        End If

        If RadioButton4.Checked = True Then
            TextBox3.Text = PrimerNum & SegundoNum
        End If

    End Sub

    Private Sub Button2_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles Button2.Click
        End
    End Sub
End Class
