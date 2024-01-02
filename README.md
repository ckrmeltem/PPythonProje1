# PPythonProje1
"""
1- Bir listeyi düzleştiren (flatten) fonksiyon yazın. Elemanları birden çok katmanlı listelerden ([[3],2] gibi) oluşabileceği gibi, non-scalar verilerden de oluşabilir. Örnek olarak:

input: [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

output: [1,'a','cat',2,3,'dog',4,5]
"""

def flatten_list(input_list)
   result[]
   for item in input_list:
       if isinstance(item, list):
          result.extend(flatten-list(item))
      else:
      result.appemd(item)
  return result

