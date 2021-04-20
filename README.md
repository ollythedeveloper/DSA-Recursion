# DSA-Recursion

1. Counting Sheep
    Input: 4
    Output: 
        4: Another sheep jumps over the fence
        3: Another sheep jumps over the fence
        2: Another sheep jumps over the fence
        1: Another sheep jumps over the fence
        All sheep jumped over the fence

2. Power Calculator
    Input: powerCalculator(10, 4)
    Output: 10,000
        10 x 10 = 100
        100 x 10 = 1000
        100 x 10 = 10000
        10000 x 10 =10,000

3. Reverse String
    Input: word
    Output: drow
        word
        dwor
        drwo
        drow

4. nth Triangular Number
    Input: 
    Output:

5. String Splitter
    Input: (800-657-8394)
    Output: ["800". "657", "8394"]
        ["800", -657-8394]
        ["800", "657", -8394]
        ["800". "657", "8394"]

6. Fibonacci
    Input: 10
    Output: 50
        1
        1, 1
        1, 1, 2
        1, 1, 2, 3
        1, 1, 2, 3, 5
        1, 1, 2, 3, 5, 8
        1, 1, 2, 3, 5, 8, 13
        1, 1, 2, 3, 5, 8, 13, 21
        1, 1, 2, 3, 5, 8, 13, 21, 29
        1, 1, 2, 3, 5, 8, 13, 21, 29, 50


7. Factorial
    Input: 8
    Output: 40320
        8 x 7 = 56
        56 x 6 = 336
        336 x 5 = 1680
        1680 x 4 = 6720
        6720 x 3 = 20160
        20160 x 2 = 40320
        40320 x 1 = 40320

8. Find a way out of the maze
    Input:
    Output:

9. Find ALL the ways out of the maze
    Input:
    Output:

10. Anagrams
    Input: east
    Output: 
        eats esat etas etsa esta esat
        aets aest ates atse aste aset 
        teas tesa tsea tsae taes tase
        sate saet seat seta stea stae

11. Organization Chart
    Input:{
        OrgHead: {
            1: Zuckerberg
            },
        DeptHeads: {
            1: Schroepfer
            2: Schrage,
            3: Sandberg
        },
        Dept1-TeamHeads: {
            1: Bosworth,
            2: Zhao
        },
        Dept2-TeamHeads: {
            1: VanDyck,
            2: Swain
        },
        Dept3-TeamHeads: {
            1: Goler,
            2: Hernandez,
            3: Moissinac,
            4: Kelly
        },
        Dept1-Team1-Emp: {
            1: Steve,
            2: Kyle,
            3: Andra
        },
        Dept1-Team2-Emp: {
            1: Richie,
            2: Sofia,
            3: Jen
        },
        Dept2-Team1-Emp: {
            1: Sabrina,
            2: Michelle,
            3: Josh
        },
        Dept2-Team2-Emp: {
            1: Blanch,
            2: Tom,
            3: Joe
        },
        Dept3-Team1-Emp: {
            1: Eddie,
            2: Julie,
            3: Annie
        },
        Dept3-Team2-Emp: {
            1: Rowi,
            2: Inga,
            3: Morgan
        },
        Dept3-Team3-Emp: {
            1: Amy,
            2: Chuck,
            3: Vinni
        },
        Dept3-Team4-Emp: {
            1: Eric,
            2: Ana, 
            3: Wes
        }
    }
    Output:
        Zuckerberg

        Zuckerberg
            Schroepfer
            Schrage
            Sandberg
        
        Zucckerberg
            Schroepfer
                Bosworth
                Zhao
            Schrage
                VanDyke
                Swain
            Sandberg
                Goler
                Hernandez
                Moissinac
                Kelley

        Zucckerberg
            Schroepfer
                Bosworth
                    Steve
                    Kyle
                    Andra
                Zhao
                    Richie
                    Sofia
                    Jen
            Schrage
                VanDyke
                    Sabrina
                    Michelle
                    Josh
                Swain
                    Blanch
                    Tom
                    Joe
            Sandberg
                Goler
                    Eddie
                    Julie
                    Annie
                Hernandez
                    Rowi
                    Inga
                    Morgan
                Moissinac
                    Amy
                    Chuck
                    Vinni
                Kelley
                    Eric
                    Ana
                    Wes 

12. Binary Representation
    Input: 3 
    Output: 11
