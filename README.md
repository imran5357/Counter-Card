# Counter-Card

<pre>
select 1 as ID,
       'Flowz' as CARD_TITLE,
       12 as CARD_VALUE,
       'fa-code-fork' ICON_CSS_CLASS,
       'primary' CSS_CLASS,
       '' CSS_STYLE
from dual

union all

select 2 as ID,
       'Instances' as CARD_TITLE,
       599 as CARD_VALUE,
       'fa-ticket' ICON_CSS_CLASS,
       'danger' CSS_CLASS,
       '' CSS_STYLE
from dual

union all

select 3 as ID,
       'Data' as CARD_TITLE,
       6875 as CARD_VALUE,
       'fa-database' ICON_CSS_CLASS,
       'success' CSS_CLASS,
       '' CSS_STYLE
from dual

union all

select 4 as ID,
       'Users' as CARD_TITLE,
       35 as CARD_VALUE,
       'fa-users' ICON_CSS_CLASS,
       'info' CSS_CLASS,
       '' CSS_STYLE
from dual

union all

select 5 as ID,
       'Users' as CARD_TITLE,
       35 as CARD_VALUE,
       'fa-users' ICON_CSS_CLASS,
       'u-color-3' CSS_CLASS,
       '' CSS_STYLE
from dual

</pre>
