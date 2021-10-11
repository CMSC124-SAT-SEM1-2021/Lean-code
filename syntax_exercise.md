<line>      -> begin <statement> end
<statement> -> <assign> ; | <assign> ; <statement>
<assign>    -> <id> = <expr>
<expr>      -> <id> * <expr> | <id> + <expr> | ( <expr> ) | <id>
<id>        -> A | B | C