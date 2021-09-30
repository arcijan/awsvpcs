import json
import dict

with open('vpcs.desc', 'r') as vpcs:
    data = json.load(vpcs)


print(data)
