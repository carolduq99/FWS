# FWS


import pandas
lines=pandas.read_csv("insects.csv",sep=";",encoding='latin1')
insects_csv= pandas.DataFrame(lines)
columns=insects_csv.columns
print(columns)
uid= insects_csv["Unique Entry ID"]
uid= insects_csv["Name"]
uid= insects_csv["Sell"]
uid= insects_csv["Where/How"]
uid= insects_csv["Weather"]
uid= insects_csv["Total Catches to Unlock"]
uid= insects_csv["Spawn Rates"]
uid= insects_csv["NH Jan"]
uid= insects_csv["NH Feb"]
uid= insects_csv["NH Mar"]
uid= insects_csv["NH Apr"]
uid= insects_csv["NH May"]
uid= insects_csv["NH Jun"]
uid= insects_csv["NH Jun"]
uid= insects_csv["NH Aug"]
uid= insects_csv["NH Sep"]
uid= insects_csv["NH Oct"]
uid= insects_csv["NH Nov"]
uid= insects_csv["NH Dec"]
uid= insects_csv["Color 1"]
uid= insects_csv["Color 2"]

        
    
print(uid)
insects=[]

for lin in lines[1:]:
    print(lin)
    uid, name, sell_price, where_how, catches2unlock, spawn_rate,when_jan,when_fev,when_mar,when_apr,when_may,when_jun,when_jul,when_aug,when_sep,when_oct,when_nov,when_dec,color1,color2
    insect={"uid":  int(uid), "name": str(name), "sell_price": int(sell_price), "where_how": str(where_how), "catches2unlock": int(catches2unlock), "spawn_rate": int(spawn_rate),"when_jan": str(when_jan),"when_fev": str(when_fev),"when_mar": str(when_mar),"when_apr": str(when_apr),"when_may": str(when_may),"when_jun": str(when_jun),"when_jul": str(when_jul),"when_aug": str(when_aug),"when_sep": str(when_sep),"when_oct": str(when_oct),"when_nov": str(when_nov),"when_dec": str(when_dec),"color1": str(color1),"color2": str(color2)}
    print(insect)
    insects.append(insect)
