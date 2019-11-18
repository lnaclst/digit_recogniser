import os
import re

path = '/Volumes/Network/courses/sp/data/'

match = re.complile(r' ')

with open(os.path.join(path, 'speakerids.txt'), 'w') as speakers:
    with open(os.path.join(path, 'info.txt'), 'r') as info:
        if match:
            # write sID to file if it matches the criteria set above
            speakers.write(path + match.group1() + '\n')