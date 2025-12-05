# Leiðbeiningar fyrir Áslaugu

1. **Búa til notendur og setja í rétta hópa**
   - Notaðu `sudo useradd` til að búa til notendur með viðeigandi fullt nafn, heimasvæði, skel og hópa.
   - Dæmi:
   ```bash
   sudo useradd -m -c "Fullt nafn" -G hópur1,hópur2 -s /usr/bin/bash notendanafn```
