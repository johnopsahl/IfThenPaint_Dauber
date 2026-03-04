Reqs:
1. system should be machine agnostic (i.e. can work with machines of any number of axes and workspace layouts)
2. motion parameters shall be stored in the grbl config and not in the machine config
3. system shall use zipped 
   
TODO:
1. ~~machine config validation: numeric ranges, fields present, type validation~~
2. ~~generate station assignments template from machine config~~
3. how to assign tool profiles to tools
4. move mixtures, components, and tool profiles to a SQLite database