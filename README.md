OrgoShmorgo
=====================
[OrgoShmorgo](http://emils.github.io/orgoShmorgo/) is an organic molecule visualizer built using D3.js. 

Getting Started
---------
OrgoShmorgo has [Vagrant](http://www.vagrantup.com/) manage all the development setup. Once you have Vagrant setup, simply run `vagrant up` in the root of your clone. You now have an OrgoShmrogo instance running on [localhost:8080](localhost:8080).


Project Goals
---------
The future goals of the project:

 - Fully IUPAC conformant naming engine
 - Addition of a lot more functional groups
 - Ability to create rings
 - Integration with Wikipedia to display data on created organic molecules 
 - 

Molecule Data Format
---------
JSON:
"2-amino-propanoic_acid": {
          "nodes": [
            {"symbol": "C", "size": 12, "bonds": 1, "id":1},
            {"symbol": "C", "size": 12, "bonds": 3, "id":2},
            {"symbol": "C", "size": 12, "bonds": 4, "id":3},
            {"symbol": "N", "size": 14, "bonds": 1, "id":4},
            {"symbol": "H", "size": 1, "bonds": 1, "id":5},
            {"symbol": "O", "size": 16, "bonds": 2, "id":6},
            {"symbol": "O", "size": 16, "bonds": 1, "id":7},
            {"symbol": "H", "size": 1, "bonds": 1, "id":8},
            {"symbol": "H", "size": 1, "bonds": 1, "id":9},
            {"symbol": "H", "size": 1, "bonds": 1, "id":10},
            {"symbol": "H", "size": 1, "bonds": 1, "id":11},
            {"symbol": "H", "size": 1, "bonds": 1, "id":12},
            {"symbol": "H", "size": 1, "bonds": 1, "id":13}
          ],
          "links": [
            {"source": 0, "target": 1,  "bondType": 1, "id": 21},
            {"source": 1, "target": 2,  "bondType": 1, "id": 22},
            {"source": 1, "target": 3,  "bondType": 1, "id": 23},
            {"source": 2, "target": 5,  "bondType": 2, "id": 24},
            {"source": 2, "target": 6,  "bondType": 1, "id": 25},
            {"source": 1, "target": 4,  "bondType": 1, "id": 26},
            {"source": 3, "target": 10, "bondType": 1, "id": 27},
            {"source": 3, "target": 11, "bondType": 1, "id": 28},
            {"source": 0, "target": 7,  "bondType": 1, "id": 29},
            {"source": 0, "target": 8,  "bondType": 1, "id": 210},
            {"source": 0, "target": 9,  "bondType": 1, "id": 211},
            {"source": 6, "target": 12,  "bondType": 1, "id": 212}
          ]
    },


License
---------

MIT © [Emil Stolarsky](http://stolarsky.com/)
