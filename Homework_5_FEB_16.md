I always think of it like this if you have a list of things that all have titles and you want
to access that information via those titles then they should be joined in a hash where you know
keys and can get at the information that you want via the keys. If you only have a list of things
that do not have titles then you should just leave them in the array as a list becuase you can
access them via the index of the array in a sense giving them a title of postion which allows them
to be accesed I guess that the rule that follows this train of thought would be that if you are
giving any info a name or a way to acces them via that key then it should be a part of a hash but
if you're just needed your data in a list without a name or key and in some sort of order then
you should not join the array into a hash but keep it as an array.

Examples:
  -List of winners by there postion in a race
  -List of items on a shelf by the order you take them off

  -List of race participants via there name, race number, and postion
  _List of items on a shelf by the brand, food group, use in kitchen
