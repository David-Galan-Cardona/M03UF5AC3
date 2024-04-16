# M03UF5AC3

## Bibliografia

Raquel Alamán Navas (2024) [UF5. POO. Classes fonamentals i persistència en BD M03.UF5. Teoria](https://docs.google.com/document/d/1JJhB0bqxqns69wKZyF-s8eacxkzv55gO-ez6QvXEvhw/edit)

Raquel Alamán Navas (2024) [GitHub Programació DAMv1](https://github.com/RaquelAlamanITB/bloc-programacio/blob/main/README.md)

No he mirat cap més documentació

## IA

Copilot:

Prompt: Amaga la segona columna. Resultat: dgvComarques.Columns[1].Visible = false;

Prompt: Guarda les dades de la cel·la al clicar-la. Resultat: 

DataGridViewRow row = dgvComarques.Rows[n]; \n /n
string nomComarca = row.Cells[2].Value.ToString();
int poblacio = Convert.ToInt32(row.Cells[3].Value);
double consumCapita = Convert.ToDouble(row.Cells[7].Value);
