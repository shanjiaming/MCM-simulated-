**Task2**

1. Function building

   1. We try to develop a funtion to describe redundancy and information cost by the header. We use the same scale, vaild information loss, to measure redundancy and information cost. And then we translate the valid information loss into redundancy. The function is called ``v2``.
      - ``maths about v2``
      - ``The meaning of v2``

   2. We discover that v2 can't fully reflect the loss, since the first travel through a edge are not counted as redundancy. Thus we make ``v1``.
      - ``maths about v1``
      - ``The meaning of v1``

2. Path enumerate

   1. We enumerate three paths. Then we proved that no possible better path then these three paths. Then we want to know which path is the best, so we calculated v1 and v2 of these path.

      - ``enumerate and prove``

      - ``calculate``
      - ``result and explanation``

**Task3**

1. Model explanation

   - - why the model can be averaged? That's because three quality.
       1. law of large numbers
       2. tricks to cut edges——always go to edges that are less visited, which can balance this tree.
       3. because the synchronization of distance and node number, the package goes to a better strategy spontaneously.
       4. tester: we can know whether it is balanced by programming
       5. even when the law is not so true, we can still try to average it manually by allocating ways according to the rate of node number.

2. Problem Abstraction
   We try to simplify the problem by extracting a ``distance-sequence`` from the web and only focus on the sequence.

   - ``extration method``
   - ``The meaning of extraction``

3. Function building

   We use the function v1 and v2 defined in ``Test2``. We will prove that in most circumstances (which we are interested in), measure with v1 and v2 have the same effect, and after that we will only use a more simple function ``vsimple`` to measure.

   - ``prove``

4. Formulation

   We want to use the ``distance sequence`` calculate the value of ``vsimple``, using our model.

5. Optimization

