One of the biggest confusion in Java programming language is whether java is **Pass by Value** or **Pass by Reference**.

构造器采用与类相同的名称。

    class Rock {
      Rock() {
        System.out.print("Rock");
      }
    }

在创建对象时：

    new Rock();
    
将会为对象分配存储空间，并调用相应的构造器。

这样确保了在你能操作对象之前，它已经被恰当地初始化了。

不接受任何参数的构造器叫做默认构造器。

构造器也能带有形式参数，以便指定如何创建对象。

Java是如何提高代码的复用性的？

组合 + 继承

Java中问题的解决都是围绕类展开的。

    class Instrument {
      public void play() {}
      static void tune(Instrument i) {
        i.play();
      }
    }
    
    public class Wind extends Instrument {
      public static void main(String[] args) {
        Wind flute = new Wind();
        Instrument.tune(flute);
      }
    }
      
向上转型