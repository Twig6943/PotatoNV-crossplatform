# Usage

1. Clone the repository with its submodules and cd into it

```sh
git clone --recurse-submodules https://github.com/mashed-potatoes/PotatoNV-crossplatform.git
cd PotatoNV-crossplatform
```

2. Create a venv, install the dependencies & run the program 

```sh
python3.13 -m venv myenv
source myenv/bin/activate
python3 -m pip install -r requirements.txt
python3.13 -m usrlock
```

Usrlock - CLI utility for unlocking Huawei devices on Kirin SoCs.
Copyright (C) 2019  Penn Mackintosh (penn5)
Copyright (C) 2020  Andrey Smirnoff (mashed-potatoes)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
