
# PoliticalDonationAnalyzer
The purpose of this project was to analyze a big dataset with parallel processing. We decided to focus on political donations. We wanted to collect, analyze, and visualize FEC data on donations given from individuals to candidates as well as committees to candidates. Details can be read in our [Part 1 Report](https://github.com/GeorgeO05/PoliticalDonationAnalyzer/blob/main/Part%201%20Report.pdf) and [Part 2 Report](https://github.com/GeorgeO05/PoliticalDonationAnalyzer/blob/main/Part%202%20%26%203%20report.pdf) as well as by watching our [Demo Video](https://www.loom.com/share/253dd2c2a2b4401c8f910286d4c2ced2).

# run it
0. start at root directory (/senior_project)
1. cd server
2. npm install
    - this will install all modules listed as dependencies in package.json.
3. npm run dev
4. cd ../client
5. npm install
6. npm start

front: http://localhost:3000

back : http://localhost:6969/api

# making changes
within src folders of each

# client/server type sharing
All types are declared in `server/src/types/Types.ts`. In client/server directories, types can be imported as follows:
```
import { testResponse } from 'types';
```
source: https://stackoverflow.com/a/65046066
