# Tests for `SENG 265`, Assignment #4

* Test 1
    * Input: `one.ics | diff test01.txt -`
    * Expected output: `test01.txt`
    * Command: `./tester4.py --start=2021/2/14 --end=2021/2/14 --file=one.ics | diff test01.txt -`

* Test 2
    * Input: `two.ics | diff test01.txt -`
    * Expected output: `test02.txt`
    * Command: `./tester4.py --start=2021/4/18 --end=2021/4/21 --file=two.ics | diff test02.txt -`

* Test 3
    * Input: `many.ics | diff test01.txt -`
    * Expected output: `test03.txt`
    * Command: `./tester4.py --start=2021/2/1 --end=2021/3/1 --file=many.ics | diff test03.txt -`

* Test 4
    * Input: `two.ics | diff test01.txt -`
    * Expected output: `test04.txt`
    * Command: `./tester4.py --start=2021/4/22 --end=2021/4/23 --file=two.ics | diff test04.txt -`

* Test 5
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test05.txt`
    * Command: `./tester4.py --start=2021/2/1 --end=2021/2/1 --file=diana-devops.ics | diff test05.txt -`

* Test 6
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test06.txt`
    * Command: `./tester4.py --start=2021/2/2 --end=2021/2/2 --file=diana-devops.ics | diff test06.txt -`

* Test 7
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test07.txt`
    * Command: `./tester4.py --start=2021/2/1 --end=2021/2/8 --file=diana-devops.ics | diff test07.txt -`

* Test 8
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test08.txt`
    * Command: `./tester4.py --start=2021/2/8 --end=2021/2/15 --file=diana-devops.ics | diff test08.txt -`

* Test 9
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test09.txt`
    * Command: `./tester4.py --start=2021/2/1 --end=2021/3/1 --file=diana-devops.ics | diff test09.txt -`

* Test 10
    * Input: `diana-devops.ics | diff test01.txt -`
    * Expected output: `test10.txt`
    * Command: `./tester4.py --start=2021/1/1 --end=2021/4/30 --file=diana-devops.ics | diff test10.txt -`

* Test 11
    * Input: `mlb.ics | diff test01.txt -`
    * Expected output: `test11.txt`
    * Command: `./tester4.py --start=2021/5/1 --end=2021/6/1 --file=mlb.ics | diff test11.txt -`

* Test 12
    * Input: `mlb.ics | diff test01.txt -`
    * Expected output: `test12.txt`
    * Command: `./tester4.py --start=2021/5/1 --end=2021/8/1 --file=mlb.ics | diff test12.txt -`

* Test 13
    * Input: `mlb.ics | diff test01.txt -`
    * Expected output: `test13.txt`
    * Command: `./tester4.py --start=2020/12/1 --end=2021/4/30 --file=mlb.ics | diff test13.txt -`
