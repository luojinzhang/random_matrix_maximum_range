# random_matrix_maximum_range
Generate random Matrix with maximum appearance twice in matrix for each number


    function shuffleMatrix()
    {
        var arr = [];
      for (var i = 0;i < 18;i++)
      {
        arr.push(i);
    arr.push(i);
      }

      var mat = [];
      for (var i = 0;i < 6;i++)
      {
        mat[i] = [];
        for (var j = 0;j < 6;j++)
        {
    var randIndex = Math.floor(Math.random()*arr.length);
    mat[i][j] = arr.splice(randIndex,1);
        }
      }
    }
