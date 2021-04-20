```uml

@startuml
start
:weather  = 天気情報;

if(weather = 0)
:快晴です;
else if(weather = 1)
:曇りです;
else if(weather = 2)
:雨ですです;
else
:不明です;
endif

end
@enduml

```
