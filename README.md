# python3_primefac

This consists of a modification of the primefac module to work in Python 3. 

The following additional changes were made: 
<ul>
<li> The multifactor function optionally takes a timeout argument. For example, multifactor ( ..., timeout=30) will timeout after 30 seconds. The default value is set to inf so if no timeout argument is supplied then it will default to how it originally operated. </li>
<li> The default bounds for the pollard_pm1 method are computed from the input n. Instead of B1=100 and B2=1000, it now uses B1 = log_2(n) and B2 = 10 * B1. </li>
</ul>
