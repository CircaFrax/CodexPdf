THIRD PARTY LICENSES - CodexPdf v1.1.0
Ce fichier DOIT accompagner toute distribution du binaire CodexPdf.exe
Place: a cote de l'exe ou dans _Doc/ ou Licences/
Ce logiciel CodexPdf lui-meme est sous LICENCE CIRCAFRAX PROPRIETARY FREEWARE v1.0 (voir LICENCE.md / LICENSE.md).
Il integre des composants open-source listés ci-dessous. Leurs licences restent applicables.

================================================================================ RESUME POUR DISTRIBUTION
Vous pouvez distribuer CodexPdf.exe gratuitement, meme en entreprise.
Vous DEVEZ garder LICENCE.md + THIRD_PARTY_LICENSES.md a cote de l'exe.
Si vous utilisez PyMuPDF, ATTENTION AGPL - voir section PyMuPDF ci-dessous.
Recommandation: passer a pypdfium2 (BSD) pour rester 100% proprietary freeware sans contrainte AGPL.
================================================================================

customtkinter - MIT License
Usage: Interface graphique moderne
Source: https://github.com/TomSchimansky/CustomTkinter
MIT License

Copyright (c) 2021-2024 Tom Schimansky

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

================================================================================ 2. Pillow (PIL) - HPND License (MIT-like permissive) Usage: Traitement images PNG/JPG Source: https://github.com/python-pillow/Pillow
The Python Imaging Library (PIL) is

Copyright @ 1997-2011 by Secret Labs AB
Copyright @ 1995-2011 by Fredrik Lundh
Pillow is the friendly PIL fork. It is

Copyright @ 2010-2024 by Jeffrey A. Clark and contributors
Like PIL, Pillow is licensed under the open source HPND License:

Permission to use, copy, modify, and distribute this software and its
documentation for any purpose and without fee is hereby granted, provided that
the above copyright notice appear in all copies and that both that copyright
notice and this permission notice appear in supporting documentation, and that
the name of the author not be used in advertising or publicity pertaining to
distribution of the software without specific, written prior permission.

THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE, INCLUDING
ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE
AUTHOR BE LIABLE FOR ANY SPECIAL, INDIRECT OR CONSEQUENTIAL DAMAGES OR ANY
DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

================================================================================ 3. pypdf - BSD 3-Clause License Usage: Fusionner, diviser, rotation, metadonnees, compression Source: https://github.com/py-pdf/pypdf
BSD 3-Clause License

Copyright (c) 2022, Martin Thoma, Fidor
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.
Neither the name of the copyright holder nor the names of its
contributors may be used to endorse or promote products derived from
this software without specific prior written permission.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

================================================================================ 4. PyMuPDF / fitz - AGPL-3.0 License (ATTENTION - CRITIQUE POUR PROPRIETARY) Usage: Visionneuse PDF et PDF->PNG (actuel) Source: https://github.com/pymupdf/PyMuPDF
ATTENTION LEGAL CRITIQUE:

PyMuPDF est sous GNU Affero General Public License v3.0 (AGPL-3.0).
Si vous incluez PyMuPDF dans CodexPdf.exe et distribuez l'exe, l'ensemble
devient AGPL-3.0, vous devez fournir le code source complet de CodexPdf sur demande,
et votre Licence Proprietary Freeware n'est plus compatible.

OPTIONS:
A) Obtenir une licence commerciale PyMuPDF aupres d'Artifex (payante) pour rester proprietary.
B) Retirer PyMuPDF de l'exe et le rendre optionnel (pip install pymupdf a part) - l'exe de base reste proprietary.
C) Remplacer PyMuPDF par pypdfium2 (BSD-3-Clause) - RECOMMANDE pour rester 100% freeware proprietary.

Texte AGPL-3.0 complet disponible sur: https://www.gnu.org/licenses/agpl-3.0.txt
Si vous gardez PyMuPDF, vous DEVEZ inclure ce fichier et proposer le source.

4bis. RECOMMANDATION: pypdfium2 - BSD 3-Clause (ALTERNATIVE A PyMuPDF) Usage: Visionneuse PDF - remplacement permissif 100% compatible proprietary freeware Source: https://github.com/pypdfium2-team/pypdfium2
BSD 3-Clause License - Meme texte que pypdf ci-dessus, permissif, commercial OK.
Copyright (c) 2022 pypdfium2-team
Permet usage dans logiciel proprietary freeware sans obligation de partager source.
C'est la solution ideale pour garder CodexPdf proprietary.

================================================================================ 5. pdf2image (optionnel) - MIT License Usage: Fallback PDF->PNG si PyMuPDF absent Source: https://github.com/Belval/pdf2image
MIT License - Meme modele que customtkinter

Copyright (c) 2017 Edouard Belval

Permission is hereby granted [...] (voir section customtkinter pour texte complet MIT)

================================================================================ 6. Python Standard Library - PSF License v2 Usage: stdlib Python Source: https://docs.python.org/3/license.html
PYTHON SOFTWARE FOUNDATION LICENSE VERSION 2

This LICENSE AGREEMENT is between the Python Software Foundation ("PSF"), and
the Individual or Organization ("Licensee") accessing and otherwise using this
software ("Python") [...]
Le texte complet est disponible sur python.org. Licence permissive autorisant
usage commercial dans logiciel proprietary.

================================================================================ FIN - OBLIGATIONS FINALES
Gardez LICENCE.md (FR) + LICENSE.md (EN) + THIRD_PARTY_LICENSES.md ensemble
Pour l'exe Windows: mettez LICENCE.txt + THIRD_PARTY_LICENSES.txt (version .txt ASCII) a cote de CodexPdf.exe
Si vous gardez PyMuPDF dans l'exe: ajoutez AGPL-3.0.txt + offre de source, ou passez en commercial
Si vous passez a pypdfium2: supprimez section AGPL, gardez BSD, vous restez 100% proprietary freeware legal
Genere le 28 juillet 2026 - CircaFrax - pour CodexPdf v1.1.0
Conforme pour distribution binaire.

