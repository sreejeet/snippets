# snippets

## VS Code snippets
```json
{
   "Python debugger without selection": {
       "prefix": "ipdb",
       "body": [
           "# fmt: off",
           "from IPython import embed;print(\"$0\");embed()# noqa",
           "# fmt: on"
       ],
       "description": "Embed ipython debugger"
   },
   "Current Time ISO": {
       "prefix": "timenow",
       "description": "Give current time in ISO format.",
       "body": [
           "$CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE $CURRENT_HOUR:$CURRENT_MINUTE:$CURRENT_SECOND",
       ]
   }
}
```
