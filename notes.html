*Github is Broken with their crap personal access tokens update*

Will push this OSED guide for WinDBG later when GH fixes their shit. Or properly documents it without me pouring through a monsterous manpage.

I have better shit to do than fuck around with this.


<html>
<ul>
<h3>Symbols</h3>
<li>Access Symbol Settings	<code> File--> Symbol File Path</code></li>
<li>Commonly used symbol path <code>C:\Symbols</code></li>
<li>Microsoft symbols path	<code>srv*c:\symbols*https://msdl.microsoft.com/download/symbols</code></li>

<li>Force download of all available symbols for all available modules <code>.reload /f</code></li>
<h3>Disassembly</h3>
<li>Disassemble a function <code>u kernel32!GetCurrentThread</code></li>
<li>Display bytes of ESP register <code>db esp</code></li>
<li>Display the bytes in words <code>dw esp</code></li>
<li>Display DWORDS <code>dd esp</code></li>
<li>Display QWORDS <code>dq 'memory address'</code></li>
<li>Display ASCII Characters <code>dc KERNELBASE</code></li>
<li>Display in WORDS format <code>dW KERNELBASE+0x40</code></li>
<li>Dump data longer than 0x80 bytes <code>dd esp L4</code></li>
<li>The dds, dps, and dqs commands display the contents of memory in the given range. This memory is assumed to be a series of addresses in the symbol table. The corresponding symbols are displayed as well. <code>dds esp L4</code></li>
<li>Dump in unicode <code>du register</code></li>
<li>dump dwords (32 bit) and interpret the result as a symbol <code>dds 'memory address or structure'</code></li>
<h3>Dumping structures in memory</h3>
<li>Dump the Thread Environment Block <code>dt ntdll!_TEB</code></li>
<li>Recursively display nested structures <code>dt -r ntdll!_TEB @$teb</code></li>
<li>Display specific field in the TEB <code>dt ntdll!_TEB @$teb ThreadLocalStoragePointer</code></li>
<li>Get size of a structure <code>?? sizeof(ntdll!_TEB)</code></li>
<h3>Modifying registers</h3>
<li>Editing contents of registers <code>ed esp 41414141</code></li>
<li>Editing using ASCII <code>ea esp abcd</code></li>
<li>Editing using unicode <code>eu esp 'unicode string'</code></li>
<h3>Searching through memory</h3>
<li>Search bytes in memory of entire application    <code>s -d 0 L?80000000 41414141</code></li>
<li>Searching for ASCII string in memory <code>s -a 0 L?80000000 "This program cannot be run in DOS mode"</code></li>
<h3>Inspecting and editing registers</h3>
<li>Dump all registers <code>r</code></li>
<li>Dump specific register <code>r ecx</code></li>
<li>dd poi(esp) display double and the data referenced from memory address, like a double pointer **ptr <code>dd poi(esp)</code></li>
<li>Specify new value for a register <code>r ecx=41414141</code></li>
<h3>Breakpoints</h3>
<li>Setting a breakpoint at the Windows WriteFile API <code>bp kernel32!WriteFile</code></li>
<li>List breakpoints <code>bl</code></li>
<li>Continue execution <code>g</code></li>
<li>Disable a breakpoint <code>bd 0</code></li>
<li>Enable a breakpoint <code>be 0</code></li>
<li>Clear a breakpoint <code>bc 0</code></li>
<li>Clear all breakpoints <code>bc *</code></li>
<li>List modules of ole32.dll <code>lm m ole32</code></li>
<li>Set breakpoint at a unresolved function <code>bu ole32!WriteStringStream</code></li>
<li>Show the number of bytes written at a breakpoint as soon as it is reached (notepad.exe) <code>bp kernel32!WriteFile ".printf \"The number of bytes written is: %p\", poi(esp + 0x0C);.echo;g"</code></li>
<li>Set hardware breakpoint with execute command and one byte in size against a writefile function <code>ba e 1 kernel32!WriteFile</code></li>
<li>Set hardware breakpoint with read command and one byte in size against a writefile function <code>ba r 1 kernel32!WriteFile</code></li>
<li>Set hardware breakpoint with write command and one byte in size against a writefile function <code>ba w 1 kernel32!WriteFile</code></li>
<h3>Stepping through the code</h3>
<li>execute one single instruction at a time and steps overfunction calls <code>p</code></li>
<li>do the same, but will also step intofunction calls <code>t</code></li>
<li>(step to next return), which allows us to fast-forward to the end of a function <code>pt</code></li>
<li>executes code until a branching instruction is reached. This includes conditional or unconditional branches, function calls, and return instructions <code>ph</code></li>
<li>Step to address command <code>pa FastBackServer!FXCLI_OraBR_Exec_Command+0x7366</code></li>
<h3>Listing Modules and Symbols in WinDbg</h3>
<li>Display all loaded modules <code>lm</code></li>
<li>Filter displayed modules that matches a wildcard <code>lm m kernel*</code></li>
<li>Dump information about a symbol <code>x kernelbase!CreateProc*</code></li>
<h3>Using WinDbg as a Calculator</h3>
<li>Perform simple math <code>? 77269bc0  -77231430</code></li>
<li>More math <code>? 77269bc0 >> 18</code></li>
<li>Convert decimal to hex <code>? 0n41414141</code></li>
<li>Convert binary to hex <code>? 0y1110100110111</code></li>
<li>Display all formats at once <code> .formats 41414141</code></li>
<li>Store the value of a mathematical calculation into a pseudo register <code>r @$t0 = (41414141 -414141) * 0n10</code></li>
<li>Display the contents of a pseudo register <code>r @$t0</code></li>
<h3>Permitting execution flow with debugger attached</h3>
<li>Allow execution to continue for memory access violations generated by a egghunter <code>sxd av</code></li>
<li>Allow execution to continue if egghunter hits a guard page <code>sxd gp</code></li>
<h3>Checking VirtualProtect or DEP enabled or ASLR</h3>
<li>Using narly <code>.load narly</code></li>
<li>Using nmod module in narly <code>!nmod</code></li>
<li>Checking virtual protect of a memory page <code>!vprot memoryaddress</code></li>
</ul>
</html>
