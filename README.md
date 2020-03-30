# vezba1
def promeniKarakter(string1):
  kar = string1[0]
  string1 = string1.replace(kar, '*')
  string1 = kar + string1[1:]

  return string1
string1=input('unesite string: ')

print(promeniKarakter(string1))
