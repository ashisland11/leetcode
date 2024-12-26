maxDepth(1)  # root = 1
   |
   +--> maxDepth(2)  # root.left = 2
          |
          +--> maxDepth(4)  # root.left = 4
          |     |
          |     +--> maxDepth(None)  # left is None -> returns 0
          |     +--> maxDepth(None)  # right is None -> returns 0
          |     +--> returns 1  # max(0, 0) + 1 = 1
          |
          +--> maxDepth(5)  # root.right = 5
          |     |
          |     +--> maxDepth(None)  # left is None -> returns 0
          |     +--> maxDepth(None)  # right is None -> returns 0
          |     +--> returns 1  # max(0, 0) + 1 = 1
          |
          +--> returns 2  # max(1, 1) + 1 = 2
   |
   +--> maxDepth(3)  # root.right = 3
          |
          +--> maxDepth(None)  # left is None -> returns 0
          +--> maxDepth(None)  # right is None -> returns 0
          +--> returns 1  # max(0, 0) + 1 = 1
   |
   +--> returns 3  # max(2, 1) + 1 = 3
