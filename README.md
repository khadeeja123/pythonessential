# pythonessential
a=10
b=20
a+b 

list1 = ["a", "b" , "c"]
list2 = [1, 2, 3]

list3 = list1 + list2
list3

list3.append(12)
list3

list4=list3.copy()
list4

list4.insert(4,"khadeeja")
list4

list4.remove(1)
list4

list4.insert(2,"mastoor")
list4

list4.count("mastoor")

list3.clear()
list3

 **Dictionaries**

dicts = {"name":"khadeeja","age":25,"number":8765478,"email":"mastoor"}

dicts

dicts["name"]

dicts.get("email")

dicts["school"]="HS PS"

dicts

len(dicts)

dicts.pop('number')

dicts.popitem()

dicts2=dicts.copy()

dicts2

dicts2.clear()
dicts2



## **Sets**

st={"km",1,2,1,3,4,2,4,5,6,"km","mast"}
st

st.add("mastoor")

st

st2=st.copy()

st2

st2.clear()

st2

st.add(7)

st.update([9,8,6])
st

st2=st.copy()

st2.issubset(st)

st2.issuperset(st)

st.difference(st2)

st.add(76)

st.difference(st2)

## **TUPLE**

tup = ("khadeeja" ,"@","mastoor")

tup

len(tup)

tup.index("@")

tup.count("khadeeja")

tup2=tuple((1,2,3,4,"km",9.8))

## BOOLEAN

a=True
a

b=False

type(a)

a or b

a and b


a and a

