```uml

@startuml
start
:weather  = 天気情報;

if(weather = 0)then(ture)
:快晴です;
else if(weather = 1)then(ture)
:曇りです;
else if(weather = 2)then(ture)
:雨です;
else
:不明です;
endif

end
@enduml

```
