Introduction to the Problem Types
-----------------------------------------------------

Please read the following, watch the videos, and try to solve the problems.

Solving Write Code Problems
==============================

If you see a problem like the one below you will need to write Python code.  The problem
will have unit tests that you can run to check that your code is working
correctly.  Click on the "Run" button to compile and run your code.  Look after
the code area for compiler errors and/or unit test results.

See the video below for an example.

.. youtube:: w9hTOJ7iJpE
    :divid: ce-ps-code
    :optional:
    :width: 650
    :height: 415
    :align: center

Try to finish writing the code for the following problem.

.. activecode:: ce-intro-sample-write-code-triple-p3
    :practice: T
    :autograde: unittest

    Write a function called ``triple(num)`` that takes a number ``num`` and
    returns the number times 3. For example, ``triple(2)`` should return 6 and
    ``triple(-1)`` should return -3.  Look below the code to check for any
    compiler errors or the results
    from the test cases.  Be sure to ``return`` the result.
    ~~~~
    def triple(num):
        # write code here

    print(triple(2))
    print(triple(-1))

    ====
    from unittest.gui import TestCaseGui
    class myTests(TestCaseGui):

        def testOne(self):
            self.assertEqual(triple(2),6,"triple(2)")
            self.assertEqual(triple(3),9,"triple(3)")
            self.assertEqual(triple(-1),-3,"triple(-1)")
            self.assertEqual(triple(0),0,"triple(0)")
            self.assertEqual(triple(11),33,"triple(11)")

    myTests().main()


Write Code with Pop-Up Mixed-up Code
=======================================

You may also see a write code problem that allows you to pop-up the
equivalent mixed-up code problem. You can use this problem to help you
solve the write code problem.  To pop-up the mixed-up code problem
click on the drop down near the top of problem.

.. youtube:: zz4ATp31_vk
    :optional:
    :divid: ce-ps-toggle
    :width: 650
    :height: 415
    :align: center

Solving Mixed-up Code Problems
==================================

If you see a problem like the one below you will need to put the mixed-up
code in the correct order on the right side. You
may need to indent the blocks as well.  There may also be extra blocks that are not
needed in a correct solution that you can leave on the left side. Click the "Check" button
to check your solution.

See the video below for an example.

.. youtube:: Rf7oWHlo-e0
    :divid: ce-ps-parsons1
    :optional:
    :width: 650
    :height: 415
    :align: center

Try to solve the following mixed-up code problem.  This problem doesn't require any indentation.

.. parsonsprob:: ce-intro-simple-parsons-no-indent-ps
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right. The text in each block
   defines the order.
   -----
   First block
   =====
   Second block
   =====
   Third block

Try to solve the following mixed-up code problem. This problem requires indentation.

.. parsonsprob:: ce-intro-simple-parsons-indent-ps
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   The text in each block defines the order and indentation.
   -----
   First block
   =====
   Second block
   =====
       Third block that needs to be indented

Try to solve the following mixed-up code problem. This problem requires indentation and has extra blocks that are not needed in a correct solution.

.. parsonsprob:: ce-intro-simple-parsons-indent-with-dist-ps
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   There is an extra block that is not needed in the correct solution.
   -----
   First block
   =====
   Second block
   =====
   Extra block that is not needed #paired: This block is not needed
   =====
       Third block that needs to be indented

The mixed-up code problems have a "Help me" button at the bottom of the
problem. Once you have checked at least three incorrect solutions you can
click the button for help.  It will remove an incorrect code block, if you used
one in your solution, or combine two blocks into one if there are more
than three blocks left.

See the video below for an example.

.. youtube:: QejZ7u642IU
    :divid: ce-ps-parsons2
    :optional:
    :width: 650
    :height: 415
    :align: center


Feedback
==================================

.. shortanswer:: ce-ex1-intro-ps-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

What to do next
============================
.. raw:: html

    <p>Click on the following link to learn how to solve different types of problems in this ebook : <b><a id="intro-class"><font size="+2">Creating Classes</font></a></b></p>

.. raw:: html

    <script type="text/javascript" >

      window.history.pushState(null, null, window.location.href);
      window.onpopstate = function () {
        window.history.go(1);
      }

      window.onload = function() {

        a = document.getElementById("intro-class")
        a.href = "class-intro-classes.html"

      };

    </script>
