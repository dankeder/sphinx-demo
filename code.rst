
Code samples
============

Literal block
-------------

Autodetected syntax::

    def roman2dec(roman):
        roman = roman.upper()
        value = 0
        multip = 1000
        for row in reversed(rnumerals):
            for (decimal_digit, roman_digit) in reversed(list(enumerate(row))):
                if roman.startswith(roman_digit):
                    value += (decimal_digit*multip)
                    roman = roman[len(roman_digit):]
                    break
            multip /= 10
        if len(roman) > 0:
            raise ValueError, 'invalid roman number'
        return value

code-block
----------

Explicit Ruby syntax:

.. code-block:: ruby
   :emphasize-lines: 4-6
   :linenos:

    ##
    # Iterator over dependency_order

    def each(&block)
      dependency_order.each(&block)
    end

    def find_name(full_name)
      @specs.find { |spec| spec.full_name == full_name }
    end

    def inspect # :nodoc:
      "#<%s:0x%x %p>" % [self.class, object_id, map { |s| s.full_name }]
    end

included file
-------------

Include file ``conf.py``, lines 20-30:

.. literalinclude:: conf.py
    :lines: 20-30

