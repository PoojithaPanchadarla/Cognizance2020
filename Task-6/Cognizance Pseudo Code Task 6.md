* `Function Main`

  * ... _Armstrong number_

  * ... _153 = [1 * 1 * 1] + [5 * 5 * 5] + [3 * 3 * 3]

  * **Declare** Integer n

  * **Declare** Integer numbers

  * **Declare** Integer num

  * **Declare** Integer original

  * **Declare** Integer sum

  * **Declare** Integer r

    

  * **Output** "How many numbers are you looking for?"

  * **Input** numbers

  * **For** n = 1 to numbers

    * *Assign* sum = 0
    * *Assign* num = n
    * *Assign* original = num
    * **While** num > 0
      * *Assign* r = num MOD 10
      * *Assign* sum = sum + (r * r * r )
      * *Assign* num = num / 10
    * End
    * **If** sum = original
      * Output ToString(sum) & " is an Armstrong number."
    * End

  * End

* `End`