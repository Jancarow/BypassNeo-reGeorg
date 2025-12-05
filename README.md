
# Anti-detection Effectiveness

> For default-generated PHP and JSP files, Neo-reGeorg already possesses strong anti-detection capabilities and requires no additional handling at this time.

![](img/vt.png)

# Usage Instructions
```
You must use the neoreg.py file included in this project. All other operations remain identical to the original version.
```
1) Use `BypassNeoASPX.py` Generate `templates/tunnel.aspx`

2）`python neoreg.py generate -k password`

3 ) `python3 neoreg.py -k password -u http://xx/tunnel.aspx`

# Related Modifications

### [BypassNeoASPX.py]

  \\-VTNo viruses detected：https://www.virustotal.com/gui/file/a7216e7f19fc068208927f221c302e5e710ab9e0da1a2762288f44b96bcc01f1?nocache=1

  \\-Modify the default text content `NeoGeorg says, 'All seems fine'` => `NEO, 'All OK'`
  
  \\-aspxAnti-detection processing（ https://xz.aliyun.com/t/11953 ）
  
### [neoreg.py]

  \\-Modify the default text content `NeoGeorg says, 'All seems fine'` => `NEO, 'All OK'`

## Disclaimer

This tool is intended solely for security research and educational purposes. Users assume all legal and related liabilities arising from its use! The author assumes no legal or related liability whatsoever!
