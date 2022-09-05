SELECT * FROM us_dollar_analysis.us_dollar_analysis;

select * from us_dollar_analysis.user
where 
Price between "108.77" and "111.61";

select * from us_dollar_analysis.user
where Open between "110.3" and "118.21";

SELECT MAX(Price) AS LargestPrice
FROM us_dollar_analysis.user;

SELECT Min(Price) AS LargestPrice
FROM us_dollar_analysis.user;

select * from us_dollar_analysis.user
where
Price between '110' and '112'
or
Open ='110.17' '111.34' '111' '110.67'
or
High = '110.34' '110.43' '110.69' '111.1';


select * from us_dollar_analysis.user
where High = '110.34' '110.43' '110.69' '111.1';


