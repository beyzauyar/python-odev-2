# python-odev-2
1-
#a=toplamsatismiktari
#b=hammaddemaliyeti
#c=bakimonarimgiderleri
#d=sevkiyatgiderleri
#e=satinalinanhizmetgiderleri
def katmadegerciro(a,b,c,d,e):
    global katmadegerciro
    katmadegerciro=a-(b+c+d+e)
    if(katmadegerciro>1000):
        print("işletme katma değer cirosu yüksek")
    elif(500<katmadegerciro<999):
        print("işletme katma değer cirosu normal")
    else:
        print("işletme katma değer cirosu düşük")
          return katmadegerciro
print("lütfen değerleri giriniz")
a=int(input("toplamsatismiktari:"))
b=int(input("hammaddemaliyeti:"))
c=int(input("bakimonarimgiderleri:"))
d=int(input("sevkiyatgiderleri:"))
e=int(input("satinalinanhizmetgiderleri:"))
sonuc=katmadegerciro(a,b,c,d,e)
print(sonuc)

2-
#a=musterilerlecalismasuresi,t=calisilansure,w=toplammusterisayisi
def musterilerlecalismasuresi2016yilihesapla(t,w):
    global a
    a=t/w
    return a
def musterilerlecalismasuresi2017yilihesapla(t,w):
    global z
    z=(t+50)/(w+20)
    return z
t=170
w=50
x=musterilerlecalismasuresi2016yilihesapla(t,w)
y=musterilerlecalismasuresi2017yilihesapla(t,w)
print(x-y)


3-
#a=yazilimgelirleri,b=finansmangelirleri,c=urunsatisgelirleri,d=calisanmaaslari,e=kiragideri,f=donanimmaliyeti,g=sponsorlukgeliri,h=eticaretgeliri i=bakimmaliyeti
def ilkaltikar(a,b,c,d,e,f):
    global ilkalti
    ilkalti=(a+b+c)-(d+e+f)
    return ilkalti
def sonaltikar(a,g,h,c,d,e,i):
    global sonalti
    sonalti=(a+g+h+c)-(d+e+i)
    return sonalti
print("Lütfen değerleri giriniz")
a=int(input("yazılım gelirlerini giriniz:"))
b=int(input("finansman gelirlerini giriniz:"))
c=int(input("ürün satış gelirlerini giriniz:"))
d=int(input("çalışan maaşlarını giriniz:"))
e=int(input("kira giderini giriniz:"))
f=int(input("donanım maliyetini giriniz"))
g=int(input("sponsorluk gelirlerini giriniz:"))
h=int(input("eticaret gelirlerini giriniz:"))
i=int(input("bakım maliyetini giriniz:"))
x=ilkaltikar(a,b,c,d,e,f)
y=sonaltikar(a,g,h,c,d,e,i)
print(x-y)
if (x-y>5000):
    print("işletme çok karlı")
elif(1000<x-y<5000):
    print("işletme karı normal")
else:
    print("işletme yeterince karda değil")

4-
#a=koltuksayisi
#b=yataksayisi
#c=dolapsayisi
#d=satilankoltuk
#e=satilanyatak
#f=satilandolap
#g=alinankoltuk
#h=alinanyatak
#ı=alinandolap
def donembasistok(a,b,c):
    global x
    x=a+b+c
    return x
def donemsonustok(a,b,c,d,e,f,g,h,ı):
    global y
    y=(a+b+c)-(d+e+f)+(g+h+ı)
    return y
def ortalamastok(x,y):
    ortalamastok=(x+y)/2
    return ortalamastok
a=30
b=30
c=30
d=25
e=20
f=10
g=10
h=15
ı=5
x=donembasistok(a,b,c)
y=donemsonustok(a,b,c,d,e,f,g,h,ı)
t=ortalamastok(x,y)
t=(x+y)/2
print(t)

