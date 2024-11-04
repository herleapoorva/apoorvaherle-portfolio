| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# General Government Debt

In this project, we examine government debt as a percentage of GDP across various nations, using data sourced from the OECD . Our objective is to depict the fiscal landscape and the impact of policies in different countries through diverse visualizations.

Further data analysis and visualization were conducted using Tableau, showcasing our proficiency with advanced visualization tools. This practical application has enhanced our ability to convey complex economic narratives effectively, an essential competency in the field of data science and economics.

## Part one: Working with web-based visualization tools and data

This bar chart illustrates the general government debt as a percentage of GDP for selected countries in the year 2022. Data is sourced from the Organization for Economic Co-operation and Development (OECD), providing a credible snapshot of fiscal health across these nations. This visualization not only sheds light on the current fiscal positions but also raises questions about the economic strategies that lead to such varied debt levels, stimulating further research and discussion.

![Image](./GGD.png)

## Working with Tableau
The heat map offered a more dynamic view of the data by using color gradients to represent different levels of government debt from 1995 to 2019. This method allowed me to quickly spot patterns and trends, such as the increase in debt levels in certain regions over time, by simply observing color changes.

## Insights and Trends: 
The table shows varied patterns of debt percentages among the countries. For instance, Japan and Greece consistently exhibit high debt ratios throughout the period, reflecting their long-term fiscal challenges. Conversely, countries like Norway and Switzerland display relatively low debt levels, indicating stronger fiscal health and conservative financial management.

## Utility of the Visualization: 
By examining changes over time, policymakers and analysts can identify periods of fiscal consolidation or expansion. This data is crucial for understanding the impact of historical economic policies on current financial stability.

This detailed view not only informs about past and present economic conditions but also serves as a foundation for predictive models concerning future governmental fiscal policies and economic outcomes.

<div class='tableauPlaceholder' id='viz1730584701991' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='General government debt - Source: OECD Data, General Government Debt Indicators, retrieved from https://www.oecd.org/en/data/indicators/general-government-debt.html'
                 src='https://public.tableau.com/static/images/Ta/TableauHW1_17305842575400/Sheet1/1_rss.png'
                 style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='TableauHW1_17305842575400/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/Ta/TableauHW1_17305842575400/Sheet1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1730584701991');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


## Part three: create your own visualization

I chose the stacked bar chart because it offers a clear, cumulative view of general government debt over time, helping to highlight overall growth trends across years. This approach allows for a straightforward analysis of how government debt has fluctuated on a broader scale, making it ideal for understanding the bigger picture. Although it doesn’t provide a breakdown by country, which limits individual trend insights, the stacked format effectively conveys the total debt trajectory and captures large-scale changes over time. My goal with this visualization was to provide an accessible, high-level perspective on government debt progression, emphasizing the collective growth without diving into individual country specifics.

<div class='tableauPlaceholder' id='viz1730677893929' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='General government debtSource: OECD Data, General Government Debt Indicators, retrieved from https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' 
                src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ta&#47;TableauHW2_17306772971950&#47;Sheet1&#47;1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz'  style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
        <param name='embed_code_version' value='3' /> 
        <param name='site_root' value='' />
        <param name='name' value='TableauHW2_17306772971950&#47;Sheet1' />
        <param name='tabs' value='no' /><param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ta&#47;TableauHW2_17306772971950&#47;Sheet1&#47;1.png' /> 
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div> 
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1730677893929');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                             
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                   
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>




