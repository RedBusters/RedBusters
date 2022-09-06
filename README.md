```cpp
class mallory{
    public:
        std::vector<std::string> pronouns = {"he", "him"};
        std::vector<std::string> code = {"C++", "Java", "Python", "Html", "Css" , "Javascript", "Php"}; // Main languages, but actually played with a lot more
        std::vector<std::string> languages = {"French", "English"}; // TODO maybe add my rusty spanish?
        mallory(int cups_of_coffee){
            if(cups_of_coffee < 3)  throw std::invalid_argument("Not enough coffee to wake up, please try again later");
            drink_coffee();
            std::cout << code_something() << std::endl;
            
        };
        ~mallory(){
            std::cout << "MUAHAHAHA I CAN'T BE DESTROYED" << std::endl;
            std::cout << "oops, as it turns out, i can, my bad :/ " << std::endl;
        }
    private:
        void drink_coffee(); // Drink coffee WARNING: can be grumpy if this function is not called enough
        std::string code_something(); // Return lines of code as a string.
};
```



- 🔭 I’m currently working on my indie game project made with Godot that i'll probably never finish. ;)
- 🌱 I’m currently learning how to write better quality code. 
- 📫 How to reach me: Via Email.
- ⚡ Fun facts: 
    - I really love making video games, i played a lot with Unreal Engine, Godot, and coding a game myself in C++ with SDL,
      but i never finished fully a game because i'm not really an artist, and i can't create a stylish ui, characters, or world/scene (2d or 3d).
      I had an idea to create a game called MEME invaders (speaks for itself, a space invaders, but full of memes) but most of the fun/popular memes 
      are copyrighted sadly enough :/
    
=> Loves open-source software
