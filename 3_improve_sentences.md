self points to the instance object itself. Use self when calling an instance object in a class or when calling that instance object.

Revised

Self is a prototype-based dynamic object-oriented programming language, environment, and virtual machine centered around the principles of simplicity, uniformity, concreteness, and liveness. Self includes a programming language, a collection of objects defined in the Self language, and a programming environment built in Self for writing Self programs. The language and environment attempt to present objects to the programmer and user in as direct and physical a way as possible. The system uses the prototype-based style of object construction.


Eg:
class Dog
  def Cow
    puts self
  end
end

Dog.new.cow
