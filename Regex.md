import java.util.regex.Matcher;  
import java.util.regex.Pattern;  
\d — соответствует любой одной цифре и заменяет собой выражение [0-9];  
\D — исключает все цифры и заменяет [^0-9];  
\w — заменяет любую цифру, букву, а также знак нижнего подчёркивания;  
\W — любой символ кроме латиницы, цифр или нижнего подчёркивания;  
\s — поиск символов пробела;  
\S — поиск любого непробельного символа.  
? — делает символ необязательным, означает 0 или 1. То же самое, что и {0,1}.  
\* — 0 или более, {0,}.  
\+ — 1 или более, {1,}.  
{n} — означает число в фигурных скобках.  
{n,m} — не менее n и не более m раз.  
*? — символ ? после квантификатора делает его ленивым, чтобы найти наименьшее количество совпадений.  
Matcher — выполняет операцию сопоставления в результате интерпретации шаблона.  
Pattern — предоставляет скомпилированное представление регулярного выражения.  
