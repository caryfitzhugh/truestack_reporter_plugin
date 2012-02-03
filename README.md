=Reporter Plugin=
This is the gem which reporter plugin gems must include in their gemfile dependencies.
You simply include it in a class which has the following method:

def plugin_exec
  ... Does something
  returns TrueStack::Metric.new ( )
  or
  TrueStack::Annotation.new ( )
  or
  ...

end

And that is all great!
