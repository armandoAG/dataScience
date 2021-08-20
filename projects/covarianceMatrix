H = torch.tensor([[2.,4.,6.,8.], [4.,8.,12.,16.], [12., 10., 5., 9.]])
print("Matriz de experimentos: ")
print(H)


def mean(v):
  return torch.mean(v, 1, True)

def covMx(H):
  mean1 = mean(H)
  res = mean1-H


  covMatrix = 1/3 * res.mm(res.transpose(0,1))

  print("\n**************** COVARIANCE MATRIX ****************")
  print(covMatrix)

  return

covMx(H)
