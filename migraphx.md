
<table width="100%" align="center">
 <tr width="100%" align="center">
    <td align="center"><img src="https://github.com/anubhavamd/migraphx_userguide/blob/main/amd_final_demo.png" width=""/><h1>MiGraphX Documentation </h1>
    </td>
 </tr>
</table>

# Table Of Contents 

</div>

<table 1>
<tr>
<th>Getting Started</th>
<th>Python User Guide</th>
<th>C++ user Guide</th>
<th>MIGraphX Driver</th>
</tr>
<tr>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#1-getting-started-guide-for-migraphx-">1. Getting Started Guide for MIGraphX </a> 
        <a href="/anubhav_migraphx_exp.md#11-introduction-">1.1. Introduction </a> 
	        <a href="/anubhav_migraphx_exp.md#anotherparagraph111">1.1.1. Documentation Roadmap</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph12">1.2. List of prerequisites</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph13">1.3. Installing pre-built packages</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph14">1.4. Building From Source</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph141">1.4.1. Use the ROCm build tool rbuild</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph142">1.4.2. Use cmake to build MIGraphX</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph143">1.4.3. Use docker</a>
 </pre>
</td>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#2-python-user-guide-">2. Python User Guide</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph21">2.1. Setting path and installing package</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph22">2.2. Defining different modules in detail</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph221">2.2.1. Shape</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph222">2.2.2. Argument</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph223">2.2.3. Target</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph224">2.2.4. Program</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph225">2.2.5. parse_onnx</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph226">2.2.6. parse_tf</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph227">2.2.7. Load</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph228">2.2.8. Save</a>
</pre>
</td>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#3-c-user-guide-">3. C++ User Guide</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph31">3.1. Defining different modules in detail</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph311">3.1.1. Shape</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph312">3.1.2. Argument</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph313">3.1.3. Target</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph314">3.1.4. Program</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph315">3.1.5. Quantize</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph316">3.1.6. parse_onnx</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph317">3.1.7. Load</a>
</pre>
</td>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#4-migraphx-driver-">4. MIGraphX Driver</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph41">4.1. Description</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph42">4.2. How to Use</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph43">4.3. Defining different modules in detail</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph431">4.3.1. Read</a>	
		<a href="/anubhav_migraphx_exp.md#anotherparagraph432">4.3.2. compile</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph433">4.3.3. Run</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph434">4.3.4. Perf</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph435">4.3.5. Verify</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph436">4.3.6. Roctx</a>
</pre>
</td>
</table 1>
<table 2>
<tr>
<th>Contributor Guide</th>	
</tr>
<td>
<pre>
<a href="/anubhav_migraphx_exp.md#5-contributor-guide-">5. Contributor Guide</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph51">5.1. MIGraphX Fundamentals</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph511">5.1.1. Location of the Examples</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph512">5.1.2. Adding Two Literals</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph513">5.1.3. Using Parameters</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph514">5.1.4. Handling Tensor Data</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph515">5.1.5. Importing From ONNX</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph52">5.2. Data Types</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph521">5.2.1. Shape</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph522">5.2.2. Literal</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph523">5.2.3. Argument</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph524">5.2.4. raw_data</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph525">5.2.5. Tensor_view</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph53">5.3. Program</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph531">5.3.1. Instruction</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph532">5.3.2. Instruction_ref</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph533">5.3.3. Program</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph534">5.3.4. Parse_onnx</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph535">5.3.5. Parse_tf</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph536">5.3.6. Onnx_options</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph537">5.3.7. Tf_options</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph54">5.4. Targets</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph541">5.4.1. Target</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph542">5.4.2. gpu::target</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph543">5.4.3. cpu::target</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph55">5.5. Passes</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph551">5.5.1. Pass</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph552">5.5.2. Dead_code_elimination</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph553">5.5.3. Eliminate_common_subexpression</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph554">5.5.4. Eliminate_concat</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph555">5.5.5. Eliminate_contiguous</a>
`		<a href="/anubhav_migraphx_exp.md#anotherparagraph556">5.5.6. Eliminate_identity</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph557">5.5.7. Eliminate_pad</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph558">5.5.8. Propagate_constant</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph559">5.5.9. Rewrite_batchnorm</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph5510">5.5.10. Rewrite_rnn</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph5511">5.5.11. Schedule</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph5512">5.5.12. Simplify_algebra</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph5513">5.5.13. Simplify_reshapes</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph56">5.6. Matchers</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph561">5.6.1. Introduction</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph562">5.6.2. Arguments</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph563">5.6.3. Binding</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph564">5.6.4. Finding matches</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph565">5.6.5. Creating matchers</a>
	<a href="/anubhav_migraphx_exp.md#subparagraph57">5.7. Tools</a>
		<a href="/anubhav_migraphx_exp.md#anotherparagraph571">5.7.1. roctx.py</a>
</td>
</pre>
</table 2>

<!--

# Table Of Contents

<table border="0" width="100%" cellpadding="0">
    <tbody>
	<tr>
	    <td height="24">
                <strong> 1. Getting Started Guide for MIGraphX </strong>
            </td>
            <td height="24">
                <strong> 2. Python User Guide </strong>
            </td>
	    <td height="24">
		<strong> 3. C++ User Guide </strong>
	    </td>
	    <td height="24">
		<strong> 4. MIGraphX Driver </strong>
	    </td>
        </tr>
	<tr>
            <td height="24">
               <a href="/anubhav_migraphx_exp.md#11-introduction-">1.1. Introduction </a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph21">2.1. Setting path and installing package</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph31">3.1. Defining different modules in detail</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph41">4.1. Description</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph111-">1.1.1. Documentation Roadmap</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph22">2.2. Defining different modules in detail</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph311">3.1.1. Shape</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph42">4.2. How to Use</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph12">1.2. List of prerequisites</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph221">2.2.1. Shape</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph312">3.1.2. Argument</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph43">4.3. Defining different modules in detail</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph13">1.3. Installing pre-built packages</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph222">2.2.2. Argument</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph313">3.1.3. Target</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph431">4.3.1. Read</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph14">1.4. Building From Source</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph223">2.2.3. Target</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph314">3.1.4. Program</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph432">4.3.2. compile</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph141">1.4.1. Use the ROCm build tool rbuild</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph224">2.2.4. Program</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph315">3.1.5. Quantize</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph433">4.3.3. Run</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph142">1.4.2. Use cmake to build MIGraphX</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph225">2.2.5. parse_onnx</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph316">3.1.6. parse_onnx</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph434">4.3.4. Perf</a>
            </td>
        </tr> 
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph143">1.4.3. Use docker</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph226">2.2.6. parse_tf</a>
            </td>
	    <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph317">3.1.7. Load</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph435">4.3.5. Verify</a>
            </td>
        </tr> 
	<tr>
            <td height="24">
                <a href=""></a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph227">2.2.7. Load</a>
            </td>
	    <td>
                <a href=""></a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph436">4.3.6. Roctx</a>
            </td>
        </tr>  
	<tr>
            <td height="24">
                <a href=""></a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph228">2.2.8. Save</a>
            </td>
	    <td>
                <a href=""></a>
            </td>
            <td>
                <a href=""></a>
            </td>
        </tr>    
    </tbody>
</table>

<table border="0" width="100%">
    <tbody>
        <tr>
            <td colspan="3" height="24" align="center">
                <strong> <a> 5. Contributor Guide</a> </strong>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph51">5.1. MIGraphX Fundamentals</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph55">5.5. Passes</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph511">5.1.1. Location of the Examples</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph551">5.5.1. Pass</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph512">5.1.2. Adding Two Literals</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph552">5.5.2. Dead_code_elimination</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph513">5.1.3. Using Parameters</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph553">5.5.3. Eliminate_common_subexpression</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph514">5.1.4. Handling Tensor Data</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph554">5.5.4. Eliminate_concat</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph515">5.1.5. Importing From ONNX</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph555">5.5.5. Eliminate_contiguous</a>
            </td>
        </tr>
        <tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph52">5.2. Data Types</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph556">5.5.6. Eliminate_identity</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph521">5.2.1. Shape</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph557">5.5.7. Eliminate_pad</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph522">5.2.2. Literal</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph558">5.5.8. Propagate_constant</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph523">5.2.3. Argument</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph559">5.5.9. Rewrite_batchnorm</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph524">5.2.4. raw_data</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph5510">5.5.10. Rewrite_rnn</a>
            </td>
        </tr>
        <tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph525">5.2.5. Tensor_view</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph5511">5.5.11. Schedule</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph53">5.3. Program</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph5512">5.5.12. Simplify_algebra</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph531">5.3.1. Instruction</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph5512">5.5.12. Simplify_algebra</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph532">5.3.2. Instruction_ref</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph5513">5.5.13. Simplify_reshapes</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph533">5.3.3. Program</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph56">5.6. Matchers</a>
            </td>
        </tr>
        <tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph534">5.3.4. Parse_onnx</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph561">5.6.1. Introduction</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph535">5.3.5. Parse_tf</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph562">5.6.2. Arguments</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph536">5.3.6. Onnx_options</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph563">5.6.3. Binding</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph537">5.3.7. Tf_options</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph564">5.6.4. Finding matches</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#subparagraph54">5.4. Targets</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph565">5.6.5. Creating matchers</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph541">5.4.1. Target</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#subparagraph57">5.7. Tools</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph542">5.4.2. gpu::target</a>
            </td>
            <td>
                <a href="/anubhav_migraphx_exp.md#anotherparagraph571">5.7.1. roctx.py</a>
            </td>
        </tr>
	<tr>
            <td height="24">
                <a href="/anubhav_migraphx_exp.md#anotherparagraph543">5.4.3. cpu::target</a>
            </td>
            <td>
                <a href=""></a>
            </td>
        </tr>
</tbody>
</table>
-->

<!--

# Table Of Contents

1. [Getting Started Guide for MIGraphX](#paragraph1)

   1.1. [Introduction](#subparagraph11)
	
      1.1.1.[Documentation Roadmap](#anotherparagraph111)
     
   1.2. [List of prerequisites](#subparagraph12)
   
   1.3. [Installing pre-built packages](#subparagraph13)
   
   1.4. [Building From Source](#subparagraph14)

     1.4.1.[Use the ROCm build tool rbuild](#anotherparagraph141)
     
     1.4.2.[Use cmake to build MIGraphX](#anotherparagraph142)

     1.4.3.[Use docker](#anotherparagraph143)
     
2. [Python User Guide](#paragraph2)

   2.1. [Setting path and installing package](#subparagraph21)
   
   2.2. [Defining different modules in detail](#subparagraph22)

     2.2.1.[Shape](#anotherparagraph221)

     2.2.2.[Argument](#anotherparagraph222)

     2.2.3.[Target](#anotherparagraph223)
 
     2.2.4.[Program](#anotherparagraph224)
     
     2.2.5.[parse_onnx](#anotherparagraph225)
     
     2.2.6.[parse_tf](#anotherparagraph226)
     
     2.2.7.[Load](#anotherparagraph227)
     
     2.2.8.[Save](#anotherparagraph228)
     
3. [C++ User Guide](#paragraph3)
   
   3.1. [Defining different modules in detail](#subparagraph31)
   
     3.1.1.[Shape](#anotherparagraph311)
     
     3.1.2.[Argument](#anotherparagraph312)
     
     3.1.3.[Target](#anotherparagraph313)
     
     3.1.4.[Program](#anotherparagraph314)
     
     3.1.5.[Quantize](#anotherparagraph315)
     
     3.1.6.[parse_onnx](#anotherparagraph316)
     
     3.1.7.[Load](#anotherparagraph317)
     
     3.1.8.[Save](#anotherparagraph318)
     
4. [MIGraphX Driver](#paragraph4)
   
    4.1. [Description](#subparagraph41)

    4.2. [How to Use](#subparagraph42)
      
    4.3. [Defining different modules in detail](#subparagraph43)
    
      4.3.1.[Read](#anotherparagraph431)
      
      4.3.2.[compile](#anotherparagraph432)
      
      4.3.3.[Run](#anotherparagraph433)
      
      4.3.4.[Perf](#anotherparagraph434)
      
      4.3.5.[Verify](#anotherparagraph435)
      
      4.3.6.[Roctx](#anotherparagraph436)
      
5. [Contributor Guide](#paragraph5)
 
   5.1. [MIGraphX Fundamentals](#subparagraph51)
   
     5.1.1.[Location of the Examples](#anotherparagraph511)
      
     5.1.2.[Adding Two Literals](#anotherparagraph512)
     
     5.1.3.[Using Parameters](#anotherparagraph513)
     
     5.1.4.[Handling Tensor Data](#anotherparagraph514)
     
     5.1.5.[Importing From ONNX](#anotherparagraph515)
     
   5.2.  [Data Types](#subparagraph52)
   
     5.2.1.[Shape](#anotherparagraph521)
     
     5.2.2.[Literal](#anotherparagraph522)
     
     5.2.3.[Argument](#anotherparagraph523)
     
     5.2.4.[raw_data](#anotherparagraph524)
     
     5.2.5.[Tensor_view](#anotherparagraph525)
     
   5.3. [Program](#subparagraph53)
   
     5.3.1.[Instruction](#anotherparagraph531)

     5.3.2.[Instruction_ref](#anotherparagraph532)
     
     5.3.3.[Program](#anotherparagraph533)
     
     5.3.4.[Parse_onnx](#anotherparagraph534)
     
     5.3.5.[Parse_tf](#anotherparagraph535)
     
     5.3.6.[Onnx_options](#anotherparagraph536)
     
     5.3.7.[Tf_options](#anotherparagraph537)
     
   5.4. [Targets](#subparagraph54)
   
     5.4.1.[Target](#anotherparagraph541)
     
     5.4.2.[gpu::target](#anotherparagraph542)
     
     5.4.3.[cpu::target](#anotherparagraph543)
     
   5.5. [Passes](#subparagraph55)
 
     5.5.1.[Pass](#anotherparagraph551)

     5.5.2.[Dead_code_elimination](#anotherparagraph552)
     
     5.5.3.[Eliminate_common_subexpression](#anotherparagraph553)
   
     5.5.4.[Eliminate_concat](#anotherparagraph554)
    
     5.5.5.[Eliminate_contiguous](#anotherparagraph555)
    
     5.5.6.[Eliminate_identity](#anotherparagraph556)
     
     5.5.7.[Eliminate_pad](#anotherparagraph557)
     
     5.5.8.[Propagate_constant](#anotherparagraph558)
   
     5.5.9.[Rewrite_batchnorm](#anotherparagraph559)
   
     5.5.10.[Rewrite_rnn](#anotherparagraph5510)
  
     5.5.11.[Schedule](#anotherparagraph5511)
   
     5.5.12.[Simplify_algebra](#anotherparagraph5512)
   
     5.5.13.[Simplify_reshapes](#anotherparagraph5513)
   
   5.6. [Matchers](#subparagraph56)
  
     5.6.1.[Introduction](#anotherparagraph561)
   
     5.6.2.[Arguments](#anotherparagraph562)
   
     5.6.3.[Binding](#anotherparagraph563)
   
     5.6.4.[Finding matches](#anotherparagraph564)
   
     5.6.5.[Creating matchers](#anotherparagraph565)
   
   5.7. [Tools](#subparagraph57)
  
     5.7.1.[roctx.py](#anotherparagraph571)
 -->
   
# 1. Getting Started Guide for MIGraphX <a name="paragraph1"></a>

# 1.1. Introduction <a name="subparagraph11"></a>

The MIGraphX execution provider uses AMD's Deep Learning graph optimization engine to accelerate ONNX model on AMD GPUs.

ONNX Runtime is an accelerator for machine learning models with multi platform support and a flexible interface to integrate with hardware-specific libraries. ONNX Runtime can be used with models from PyTorch, Tensorflow/Keras, TFLite, scikit-learn, and other frameworks.

The document also contains an Python User guide, C++ user Guide, MIGraphX Driver and Contributor Guide.

## 1.1.1. Documentation Roadmap <a name="anotherparagraph111"></a>

The following is a list of MIGraphX documents in the suggested reading order:

-   Getting Started Guide (this document): In this section we have introduce MIGraphX, ONNX Runtime.
-   Python User Guide: In this section we will be defining different modules like shape, target, argument, save, load, etc.
-   C++ Reference: Describe modules like shape, argument, load, parse_onnx, etc.
-   MIGraphX Driver: Under this section we will cover modules like perf, verify, roctx, etc.
-   Contributor’s Guide: Provides detailed information about MIGraphX Fundamentals, datatypes, operators, targets, etc.

# 1.2. List of prerequisites <a name="subparagraph12"></a>

The following is a list of prerequisites required to build MIGraphX source.

-   [ROCm cmake modules](https://github.com/RadeonOpenCompute/rocm-cmake) required
-   [MIOpen](https://github.com/ROCmSoftwarePlatform/MIOpen) for running on the GPU
-   [rocBLAS](https://github.com/ROCmSoftwarePlatform/rocBLAS) for running on the GPU
-   [HIP](https://github.com/ROCm-Developer-Tools/HIP) for running on the GPU
-   [Protobuf](https://github.com/google/protobuf) for reading onnx files
-   [Half](http://half.sourceforge.net/) - IEEE 754-based half-precision floating point library
-   [pybind11](https://pybind11.readthedocs.io/en/stable/) - for python bindings
-   [JSON](https://github.com/nlohmann/json) - for model serialization to json string format
-   [MessagePack](https://msgpack.org/index.html) - for model serialization to binary format

# 1.3. Installing pre-built packages <a name="subparagraph13"></a>

With ROCm installed correctly, MIGraphX binaries can be installed on Ubuntu with the following command:
```
sudo apt update && sudo apt install -y migraphx
```
then the header files and libs are installed under ``` /opt/rocm-\<version\> ```, where \<version\> is the ROCm version.

# 1.4. Building From Source <a name="subparagraph14"></a>

There are three ways to build the MIGraphX sources.

-   [Use the ROCm build tool](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX#use-the-rocm-build-tool-rbuild)

    This approach uses rbuild to install the prerequisites and build the libs with just one command.

-   [Use cmake](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX#use-cmake-to-build-migraphx)

    This approach uses a script to install the prerequisites, then use cmake to build the source.

-   [Use docker](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX#use-docker)

    This approach builds a docker image with all prerequisites installed, then build the MIGraphX sources inside a docker container.

### 1.4.1. Use the ROCm build tool rbuild <a name="anotherparagraph141"></a>

In this approach, we use the rbuild build tool to build MIGraphX. The specific steps are as follows:

Install rocm-cmake, pip3, rocblas, and miopen-hip with the command
```
sudo apt update && sudo apt install -y rocm-cmake python3-pip rocblas miopen-hip
```
Install rbuild (sudo may be required here.)
```
pip3 install https://github.com/RadeonOpenCompute/rbuild/archive/master.tar.gz
```
Build MIGraphX source code
```
rbuild build -d depend -B build --cxx=/opt/rocm/llvm/bin/clang++
```
then all the prerequisites are in the folder depend, and MIGraphX is built in the build directory.

Note that for ROCm3.7 and later releases, Ubuntu 18.04 or later releases are needed. Upgrade to Ubuntu 18.04 is available at [Upgrade Ubuntu to 18.04](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/wiki/Upgrade-to-Ubuntu-18.04-for-ROCM3.7-or-later-releases)

Also note that you may meet the error of rbuild: command not found. It is because rbuild is installed at ``` \$HOME/.local/bin ```, which is not in PATH. You can either export PATH as export ``` PATH=\$HOME/.local/bin:\$PATH ``` to add the folder to PATH or add the option ``` --prefix /usr/local ``` in the pip3 command when installing rbuild.

### 1.4.2. Use cmake to build MIGraphX <a name="anotherparagraph142"></a>

If using this approach, we need to install the prerequisites, configure the cmake, and then build the source.

#### 1. Installing the prerequisites

For convenience, the prerequisites can be built automatically with rbuild as:
```
rbuild build -d depend --cxx=/opt/rocm/llvm/bin/clang++
```
then all the prerequisites are in the folder depend, and they can be used in the cmake configuration as ``` -DCMAKE_PREFIX_PATH=depend ```.

If you have sudo access, as an alternative to the rbuild command, you can install the prerequisites just like in the dockerfile by calling ``` ./tools/install_prereqs.sh ```.

(Note that this script is for Ubuntu. By default, all prerequisites are installed at the default location ``` /usr/local ``` and are accessible by all users. For the default location, sudo is required to run the script. You can also specify a location at which the prerequisites are installed with ``` ./tools/install_prereqs.sh \$your_loc. ```)

#### 2. Building MIGraphX source and install libs

With the above prerequisites installed, we can build source as:

Go to the project folder and create a build directory:
```
mkdir build
cd build
```
Configure the cmake. If the prerequisites are installed at the default location /usr/local, the command is:
```
CXX=/opt/rocm/llvm/bin/clang++ cmake..
```
Otherwise, you need to set ``` -DCMAKE_PREFIX_PATH=\$your_loc ``` to configure the cmake.

Build MIGraphX source code
```
make -j\$(nproc)
```
Correctness can be verified as:
```
make -j\$(nproc) check
```
MIGraphX libs can be installed as:
```
make install
```
### 1.4.3. Use docker <a name="anotherparagraph143"></a>

The easiest way to setup the development environment is to use docker. With the dockerfile, you can build a docker image as:
```
docker build -t migraphx.
```
Then to enter the developement environment use docker run:
```
docker run --device='/dev/kfd' --device='/dev/dri' -v=\`pwd\`:/code/AMDMIGraphX -w /code/AMDMIGraphX --group-add video -it migraphx
```
In the docker container, all the required prerequisites are already installed, so users can just go to the folder /code/AMDMIGraphX and follow the steps in the above [Build MIGraphX source and install libs](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX#building-migraphx-source-and-install-libs) section to build MIGraphX source.c

# 2. Python User Guide <a name="paragraph2"></a>

# 2.1. Setting path and installing package <a name="subparagraph21"></a>

To use MIGraphX's Python module, please either set PYTHONPATH or use .deb package as explained below:

-   Setting PYTHONPATH:
```
export PYTHONPATH=/opt/rocm/lib:\$PYTHONPATH
```
-   Creating and installing the package:

To create deb package:
```
make package
```
This will provide the path of .deb package.

To install:
```
dpkg -i \<path_to_deb_file\>
```
# 2.2 Defining different modules in detail <a name="subparagraph22"></a>

## 2.2.1. Shape <a name="anotherparagraph221"></a>

```
classmigraphx.shape(type,lens,strides=None)
```
Describes the shape of a tensor. This includes size, layout, and data type/
```
migraphx.type()
```
An integer that represents the type

##### Return type: int
	
```
migraphx.lens()
```
A list of the lengths of the shape

##### Return type: list[int]

```
migraphx.strides()
```
A list of the strides of the shape

##### Return type: list[int]

```
migraphx.elements()
```
The number of elements in the shape

##### Return type: int

```
migraphx.bytes()
```
The number of bytes the shape uses

##### Return type: int

```
migraphx.type_size()
```
The number of bytes one element uses

##### Return type: int

```
migraphx.packed()
```
Returns true if the shape is packed.

##### Return type: bool

```
migraphx.transposed()
```
Returns true if the shape is transposed.

##### Return type: bool

```
migraphx.broadcasted()
```
Returns true if the shape is broadcasted.

##### Return type: bool

```
migraphx.standard()
```
Returns true if the shape is a standard shape. That is, the shape is both packed and not transposed.

##### Return type: bool

```
migraphx.scalar()
```
Returns true if all strides are equal to 0 (scalar tensor).

##### Return type: bool

## 2.2.2. Argument <a name="anotherparagraph222"></a>

```
classmigraphx.argument(data)
```
Construct an argument from a python buffer. This can include numpy arrays.

```
migraphx.get_shape()
```
Returns the shape of the argument.

##### Return type: shape

```
migraphx.tolist()
```
Convert the elements of the argument to a python list.

##### Return type: list

```
migraphx.generate_argument(s**, **seed=0)
```
Generate an argument with random data.

##### Parameters:
-    s (shape) – Shape of argument to generate.

-    seed (int) – The seed used for random number generation

##### Return type: argument

## 2.2.3. Target <a name="anotherparagraph223"></a>

```
Class migraphx.target
```
This represents the compiliation target.

```
migraphx.get_target(name)
```
Constructs the target.

##### Parameters: 
-   name (str) – The name of the target to construct. This can either be ‘gpu’ or ‘ref’.

##### Return type: target

## 2.2.4. Program <a name="anotherparagraph224"></a>

```
class migraphx.program
```
Represents the computation graph to be compiled and run.

```
migraphx.clone()
```
Make a copy of the program

##### Return type: program

```
migraphx.get_parameter_shapes()
```
Get the shapes of all the input parameters in the program.

##### Return type: dict[str,shape]
```
migraphx.get_shape()
```
Get the shape of the final output of the program.

##### Return type: shape
```
migraphx.compile(t, offload_copy=True, fast_math=True)
```
Compiles the program for the target and optimizes it.

##### Parameters

-   t (target) – This is the target to compile the program for.
-   offload_copy (bool) – For targets with offloaded memory(such as the gpu), this will insert instructions during compilation to copy the input parameters to the offloaded memory and to copy the final result from the offloaded memory back to main memory.
-   fast_math (bool) – Optimize math functions to use faster approximate versions. There may be slight accuracy degredation when enabled.

```
migraphx.run(params)
```
Run the program.

##### Parameters: 
- params (dict[str,argument]) – This is a map of the   input parameters which will be used when running the program.

- Returns: The result of the last instruction.

##### Return type: argument

```
migraphx.quantize_fp16(prog, ins_names=['all'])
```
Quantize the program to use fp16.

##### Parameters: 
-    prog (program) – Program to quantize.

-    ins_names (list[str]) – List of instructions to quantize.

```
migraphx.quantize_int8(prog, t, calibration=[], ins_names=['dot', 'convolution'])
```
Quantize the program to use int8.

##### Parameters:

-   prog (program) – Program to quantize.
-   t (target) – Target that will be used to run the calibration data.
-   calibration (list[dict[str,argument]]) – Calibration data used to decide the parameters to the int8 optimization.
-   ins_names (list[str]) – List of instructions to quantize.

## 2.2.5. parse_onnx <a name="anotherparagraph225"></a>

```
migraphx.parse_onnx(filename, default_dim_value=1, map_input_dims={}, skip_unknown_operators=false, print_program_on_error=false)
```
Load and parse an onnx file.

##### Parameters:

-   filename (str) – Path to file.
-   default_dim_value (str) – default batch size to use (if not specified in onnx file).
-   map_input_dims (str) – Explicitly specify the dims of an input.
-   skip_unknown_operators (str) – Continue parsing onnx file if an unknown operator is found.
-   print_program_on_error (str) – Print program if an error occurs.

##### Return type: program

## 2.2.6. parse_tf <a name="anotherparagraph226"></a>

```
migraphx.parse_tf(filename, is_nhwc=True, batch_size=1)
```
Load and parse an tensorflow protobuf file file.

##### Parameters:

-   filename (str) – Path to file.
-   is_nhwc (bool) – Use nhwc as default format.
-   batch_size (str) – default batch size to use (if not specified in protobuf).

##### Return type: program

## 2.2.7. Load <a name="anotherparagraph227"></a>

```
migraphx.load(filename, format='msgpack')
```
Load a MIGraphX program

##### Parameters:

-   filename (str) – Path to file.
-   format (str) – Format of file. Valid options are msgpack or json.

##### Return type: program

## 2.2.8. Save <a name="anotherparagraph228"></a>

```
migraphx.save(p, filename, format='msgpack')
```
Save a MIGraphX program

##### Parameters:

-   p (program) – Program to save.
-   filename (str) – Path to file.
-   format (str) – Format of file. Valid options are msgpack or json.

# 3. C++ User Guide <a name="paragraph3"></a>

# 3.1 Defining different modules in detail <a name="subparagraph31"></a>

## 3.1.1 Shape <a name="anotherparagraph311"></a>

```
enum migraphx_shape_datatype_t
```
An enum to represent the different data type inputs.

Values:

```
enumerator migraphx_shape_tuple_type
```

```
enumerator migraphx_shape_bool_type
```

```
enumerator migraphx_shape_int64_type
```

```
enumerator migraphx_shape_uint32_type
```

```
enumerator migraphx_shape_uint64_type
```

```
struct migraphx::shape : public migraphx::handle_base\<\>
```
Describe shape of tensor.

A shape consists of a data type, lengths of multi-dimension tensor, and strides

##### Public Functions

```
inline shape()
```

```
inline shape(const migraphx_shape \*p)
```

```
inline shape(migraphx_shape \*p, own)
```

```
inline shape(migraphx_shape \*p, borrow)
```

```
inline shape(migraphx_shape_datatype_t type)
```
Construct a scalar shape.

```
inline shape(migraphx_shape_datatype_t type, std::vector\<size_t\> plengths)
```

Construct a shape with its type and lengths. The strides are automatically computed assumming a packed layout.

```
inline shape(migraphx_shape_datatype_t type, std::vector<size_t> plengths, std::vector<size_t> pstrides)
```

```
inline std::vector<size_t> lengths() const
```

```
inline std::vector<size_t> strides() const
```

```
inline migraphx_shape_datatype_t type() const
```

```
inline size_t bytes() const
```

##### Friends

```
inline friend friend bool operator== (const shape &px, const shape &py)
```

```
inline friend friend bool operator!= (const shape &px, const shape &py)
```

## 3.1.2 Argument <a name="anotherparagraph312"></a>

`` raw buffer of data with a shape.

##### Public Functions

```
inline argument()
```

```
inline argument(migraphx_argument \*p, borrow)
```

```
inline argument(migraphx_argument \*p, own)
```

```
inline argument(const migraphx_argument \*p)
```

```
inline argument([**shape**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx5shapeE) pshape, void \*pbuffer)
```

```
inline [**shape**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx5shapeE) get_shape() const
```

```
inline char \*data() const
```

##### Public Static Functions

```
static inline[**argument**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx8argumentE) generate([**shape**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx5shapeE) ps, size_t pseed = 0)
```
Generate an argument using random data.

##### Friends
```
inline friend friend bool operator== (const argument &px,const argument &py)
```

```
inline friend friend bool operator!= (const argument &px,const argument &py)
```

## 3.1.3 Target  <a name="anotherparagraph313"></a>

```
struct migraphx::target : public migraphx::handle_base\<\>
```
target for compilation.

##### Public Functions

```
inline target()
```

```
inline target(migraphx_target *p, own)
```

```
inline target(migraphx_target *p, borrow)
```

```
inline target(const char *name)
```
Construct a target from its name.

## 3.1.4 Program  <a name="anotherparagraph314"></a>

```
struct migraphx::program_parameter_shapes : public migraphx::handle_base\<\>
```

Public Functions

```
inline program_parameter_shapes()
```

```
inline program_parameter_shapes(migraphx_program_parameter_shapes *p, own)
```

```
inline program_parameter_shapes(migraphx_program_parameter_shapes *p, borrow)
```

```
inline size_t size() const
```

```
inline [**shape**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx5shapeE) operator[](const char *pname) const
```

```
inline std::vector\<const char\*\> names() const
```

```
struct migraphx::program_parameters : public migraphx::handle_base\<\>
```

A class to construct the inputs parameters for a program.


##### Public Functions

```
inline program_parameters(migraphx_program_parameters *p, own)
```

```
inline program_parameters(migraphx_program_parameters *p, borrow)
```

```
inline program_parameters(migraphx_program_parameters *p)
```

```
inline program_parameters()inline program_parameters(std::initializer_list\<std::pair\<std::string, [**argument**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx8argumentE) >>l)
```

Construct the parameters from initializer_list.

```
inline void add(const char *pname, const [**argument**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx8argumentE) &pargument) const
```

Add a new parameter.

```
struct migraphx_compile_options
```

##### Public Functions

```
template\<class ...Ts\>  
inline migraphx_compile_options([**Ts**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4IDpEN24migraphx_compile_options24migraphx_compile_optionsEDpRR2Ts)&&... xs)
```

##### Public Members

```
migraphx::compile_options object
```

```
struct migraphx::program : public migraphx::handle_base\<\>
```

A program represents the all computation graphs to be compiled and executed.

##### Public Functions

```
inline program()
```

```
inline program(migraphx_program *p, own)
```

```
inline program(migraphx_program *p, borrow)
```

```
inline void compile(const [**target**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx6targetE) &ptarget, const compile_options &poptions) const
```

Compile the program for a specific target to be ran on.

```
inline void compile(const [**target**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx6targetE) &ptarget) const
```

Compile the program for a specific target to be ran on.

```
inline program_parameter_shapes get_parameter_shapes() const
```

Return the shapes for the input parameters.

```
inline shapes get_output_shapes() const
```

Get the shapes of all the outputs returned by this program.

```
inline arguments eval(const program_parameters \&pparams) const
```

Run the program using the inputs passed in.

```
inline void print() const
```

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) sort()
```

```
inline module get_main_module()
```

##### Friends

```
inline friend friend bool operator== (const program &px, const program &py)
```

```
inline friend friend bool operator!= (const program &px, const program &py)
```

## 3.1.5 Quantize  <a name="anotherparagraph315"></a>

```
struct migraphx::quantize_op_names : public migraphx::handle_base\<\>
```

##### Public Functions

```
inline quantize_op_names()
```

```
inline quantize_op_names(migraphx_quantize_op_names *p, own)
```

```
inline void add(const std::string \&name)
```

```
inline void migraphx::quantize_fp16(const [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) &prog)
```
Quantize program to use fp16.

```
inline void migraphx::quantize_fp16(const [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) &prog, const[ quantize_op_names ](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx17quantize_op_namesE) &names)
```

Quantize program to use fp16.

```
struct migraphx::quantize_int8_options : public migraphx::handle_base\<\>
```

Options to be passed when quantizing for int8.

##### Public Functions

```
inline quantize_int8_options()
```

```
inline quantize_int8_options(migraphx_quantize_int8_options *p, own)
```

```
inline quantize_int8_options(migraphx_quantize_int8_options *p, borrow)
```

```
inline void add_op_name(const std::string \&name)
```

Add an operator that should be quantized.

```
inline void add_calibration_data(const program_parameters \&pp)
```

Add calibrartion data to be used for quantizing.

##### Public Members

```
std::vector\<parameter_map\> calibration = {}
```

```
std::vector\<std::string\> op_names = {}
```

```
inline void migraphx::quantize_int8(const [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) &prog, const [**target**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx6targetE) &ptarget, const [**quantize_int8_options**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx21quantize_int8_optionsE) &options)
```

Quantize program to use int8.

## 3.1.6 parse_onnx  <a name="anotherparagraph316"></a>

```
struct migraphx::onnx_options : public migraphx::handle_base\<\>
```
Options for parsing onnx options.

##### Public Functions

```
inline onnx_options()
```

```
inline onnx_options(migraphx_onnx_options *p, own)
```

```
inline void set_input_parameter_shape(const std::string \&name, std::vector\<std::size_t\> dim)
```

Make onnx parser treat an inputs with a certain dimensions.

```
inline void set_default_dim_value(unsigned int value)
```

When there is a dimension parameter, then use this default value.

```
inline void set_default_loop_iterations(int64_t value)
```

Set default max iteration number for the loop operator.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx(const char *filename)
```

Parse an onnx file into a migraphx program.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx(const char *filename, const migraphx::onnx_options&options)
```

Parse an onnx file into a migraphx program.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx_buffer(const std::string &buffer)
```

Parse a buffer of memory as an onnx file.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx_buffer(const std::string &buffer, const migraphx::onnx_options &options)
```

Parse a buffer of memory as an onnx file.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx_buffer(const void *data, size_t size)
```

Parse a buffer of memory as an onnx file.

```
inline [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) migraphx::parse_onnx_buffer(const void *data, size_t size, const migraphx::onnx_options &options)
```

Parse a buffer of memory as an onnx file.

## 3.1.7 Load  <a name="anotherparagraph317"></a>

```
struct migraphx_file_options
```
##### Public Functions

```
template\<class ...Ts\>  
inline migraphx_file_options([**Ts**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4IDpEN21migraphx_file_options21migraphx_file_optionsEDpRR2Ts)&&... xs)
```

##### Public Members

```
migraphx::file_options object
```

```
inline program migraphx::load(const char *filename)
```
Load a saved migraphx program from a file.

## 3.1.8 Save  <a name="anotherparagraph318"></a>

```
inline void migraphx::save(const [**program**](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/reference/cpp.html#_CPPv4N8migraphx7programE) &p, const char *filename)
```
Save a program to a file.

# 4. MIGraphX Driver <a name="paragraph4"></a>

# 4.1 Description <a name="subparagraph41"></a>

The MIGraphX driver is a tool that allows you to utilize many of the core functions of MIGraphX without having to write your own program.

# 4.2 How to Use <a name="subparagraph42"></a>

The MIGraphX driver is installed with MIGraphX and can be found in */opt/rocm/bin/migraphx-driver*, or in *AMDMIGraphX/build/bin/migraphx-driver* after building the source code.

# 4.3 Defining different modules in detail <a name="subparagraph43"></a>

## 4.3.1 Read <a name="anotherparagraph431"></a>

Loads and prints input graph.

```
<input file>
```

File to load

```
--model [resnet50|inceptionv3|alexnet]
```

Load model

```
--onnx
```

Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1)
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int]
```

Trim instructions from the end (Default: 0)

```
--input-dim [std::vector<std::string>]
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O
```

Optimize when reading

```
--graphviz, -g
```

Print out a graphviz representation.

```
--brief
```

Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text
```

Print out program in text format.

```
--binary
```

Print out program in binary format.

```
--output, -o [std::string]
```

Output to file.

## 4.3.2 compile <a name="anotherparagraph432"></a>

Compiles and prints input graph.

```
<input file>
```

File to load

```
--model [resnet50|inceptionv3|alexnet]
```

Load model

```
--onnx
```
Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1)
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int] 
```

Trim instructions from the end (Default: 0)

```
--input-dim [std::vector<std::string>] 
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O 
```

Optimize when reading

```
--graphviz, -g 
```

Print out a graphviz representation.

```
--brief 
```
Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text 
```

Print out program in text format.

```
--binary 
```

Print out program in binary format.

```
--output, -o [std::string] 
```

Output to file.

```
--fill0 [std::vector<std::string>] 
```

Fill parameter with 0s

```
--fill1 [std::vector<std::string>] 
```

Fill parameter with 1s

```
--gpu
```

Compile on the gpu

```
--cpu
```

Compile on the cpu

```
--ref 
```

Compile on the reference implementation

```
--enable-offload-copy 
```

Enable implicit offload copying

```
--disable-fast-math 
```

Disable fast math optimization

```
--fp16
```

Quantize for fp16

```
--int8
```

Quantize for int8

## 4.3.3 Run <a name="anotherparagraph433"></a>

Loads and prints input graph.

```
<input file>
```

File to load

```
--model 
```

Load model

```
--onnx
```

Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1) 
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators 
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int] 
```

Trim instructions from the end (Default: 0)


```
--input-dim [std::vector<std::string>] 
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O 
```

Optimize when reading

```
--graphviz, -g 
```

Print out a graphviz representation.

```
--brief 
```

Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text 
```

Print out program in text format.

```
--binary
```

Print out program in binary format.

```
--output, -o [std::string] 
```

Output to file.

```
--fill0 [std::vector<std::string>] 
```

Fill parameter with 0s

```
--fill1 [std::vector<std::string>] 
```

Fill parameter with 1s

```
--gpu
```

Compile on the gpu

```
--cpu
```

Compile on the cpu

```
--ref 
```

Compile on the reference implementation

```
--enable-offload-copy 
```

Enable implicit offload copying

```
--disable-fast-math 
```

Disable fast math optimization

```
--fp16 
```

Quantize for fp16

```
--int8 
```

Quantize for int8

## 4.3.4 Perf <a name="anotherparagraph434"></a>

Compiles and runs input graph then prints performance report.

```
\<input file\> [https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/driver.html\#cmdoption-migraphx-driver-perf-arg-input](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/driver.html#cmdoption-migraphx-driver-perf-arg-input)
```

File to load

```
--model 
```

Load model

```
--onnx
```

Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1) 
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators 
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int] 
```

Trim instructions from the end (Default: 0)

```
--input-dim [std::vector<std::string>] 
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O 
```

Optimize when reading

```
--graphviz, -g 
```

Print out a graphviz representation.

```
--brief 
```

Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text
```

Print out program in text format.

```
--binary 
```

Print out program in binary format.

```
--output, -o [std::string] 
```

Output to file.

```
--fill0 [std::vector<std::string>]
```

Fill parameter with 0s

```
--fill1 [std::vector<std::string>] 
```

Fill parameter with 1s

```
--gpu
```

Compile on the gpu

```
--cpu
```

Compile on the cpu

```
--ref 
```

Compile on the reference implementation

```
--enable-offload-copy 
```

Enable implicit offload copying

```
--disable-fast-math 
```

Disable fast math optimization

```
--fp16 
```

Quantize for fp16

```
--int8 
```

Quantize for int8

```
--iterations, -n [unsigned int] 
```

Number of iterations to run for perf report (Default: 100)

## 4.3.5 Verify <a name="anotherparagraph435"></a>

Runs reference and CPU or GPU implementations and checks outputs for consistency.

```
<input file>
```

File to load

```
--model [resnet50|inceptionv3|alexnet] 
```

Load model

```
--onnx
```

Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1) 
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators 
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int] 
```

Trim instructions from the end (Default: 0)

```
--input-dim 
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O 
```

Optimize when reading

```
--graphviz, -g 
```

Print out a graphviz representation.

```
--brief 
```

Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text 
```

Print out program in text format.

```
--binary 
```

Print out program in binary format.

```
--output, -o [std::string] 
```

Output to file.

```
--fill0 [std::vector<std::string>] 
```

Fill parameter with 0s

```
--fill1 [std::vector<std::string>] 
```

Fill parameter with 1s

```
--gpu
```

Compile on the gpu

```
--cpu
```

Compile on the cpu

```
--ref 
```

Compile on the reference implementation

```
--enable-offload-copy 
```

Enable implicit offload copying

```
--disable-fast-math 
```

Disable fast math optimization

```
--fp16 
```
Quantize for fp16

```
--int8 
```

Quantize for int8

```
--tolerance [double] 
```

Tolerance for errors (Default: 80)

```
-i, --per-instruction 
```

Verify each instruction

```
-r, --reduce 
```

Reduce program and verify

## 4.3.6 Roctx <a name="anotherparagraph436"></a>

Provides marker information for each operation, allowing MIGraphX to be used with rocprof for performance analysis. This allows user to get GPU-level kernel timing information. An example command line combined with rocprof for tracing purposes is given below:

```
/opt/rocm/bin/rocprof --hip-trace --roctx-trace --flush-rate 1ms --timestamp on -d \<OUTPUT_PATH\> --obj-tracking on /opt/rocm/bin/migraphx-driver roctx \<ONNX_FILE\> \<MIGRAPHX_OPTIONS\>
```

After ``` rocprof ``` is run, the output directory will contain trace information for HIP, HCC and ROCTX in seperate ```.txt``` files. To understand the interactions between API calls, it is recommended to utilize ``` roctx.py ``` helper script as desribed in dev/tools:rocTX section.

```
<input file> 
```

File to load

```
--model 
```

Load model

```
--onnx
```

Load as onnx

```
--tf
```

Load as tensorflow

```
--migraphx
```

Load as MIGraphX

```
--migraphx-json
```

Load as MIGraphX JSON

```
--batch [unsigned int] (Default: 1) 
```

Set batch size for model

```
--nhwc
```

Treat tensorflow format as nhwc

```
--skip-unknown-operators 
```

Skip unknown operators when parsing and continue to parse.

```
--nchw
```

Treat tensorflow format as nchw

```
--trim, -t [unsigned int] 
```

Trim instructions from the end (Default: 0)

```
--input-dim [std::vector<std::string>] 
```

Dim of a parameter (format: “@name d1 d2 dn”)

```
--optimize, -O 
```

Optimize when reading

```
--graphviz, -g 
```

Print out a graphviz representation.

```
--brief 
```

Make the output brief.

```
--cpp
```

Print out the program as cpp program.

```
--json
```

Print out program as json.

```
--text 
```
Print out program in text format.

```
--binary 
```

Print out program in binary format.

```
--output, -o [std::string] 
```

Output to file.

```
--fill0 [std::vector<std::string>] 
```

Fill parameter with 0s

```
--fill1 [std::vector<std::string>] 
```

Fill parameter with 1s

```
--gpu
```

Compile on the gpu

```
--cpu
```

Compile on the cpu

```
--ref 
```

Compile on the reference implementation

```
--enable-offload-copy 
```

Enable implicit offload copying

```
--disable-fast-math
```

Disable fast math optimization

```
--fp16 
```

Quantize for fp16

```
--int8 
```

Quantize for int8

# 5. Contributor Guide <a name="paragraph5"></a>

# 5.1 MIGraphX Fundamentals <a name="subparagraph51"></a>

MIGraphX provides an optimized execution engine for deep learning neural networks. We will cover some simple operations in the MIGraphX framework here. For a quick start guide to using MIGraphX, look in the example directory:

https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/tree/develop/examples/migraphx.

## 5.1.1 Location of the Examples <a name="anotherparagraph511"></a>

The ``` ref_dev_examples.cpp ``` can be found in the test directory ``` (/test) ```. The executable file ``` test_ref_dev_examples ``` based on this file will be created in the ``` bin/ ``` of the build directory after running ``` make -j\$(nproc) test_ref_dev_examples ```. The executable will also be created when running ``` make -j\$(nproc) check ```, alongside with all the other tests. Directions for building MIGraphX from source can be found in the main README file:

https://github.com/ROCmSoftwarePlatform/AMDMIGraphX\#readme.

## 5.1.2 Adding Two Literals <a name="anotherparagraph512"></a>

A program is a collection of modules, which are collections of instructions to be executed when calling ``` eval ```. Each instruction has an associated ``` operation ``` which represents the computation to be performed by the instruction.

We start with a snippet of the simple ``` add_two_literals() ``` function:

```
// create the program and get a pointer to the main module
migraphx::program p;
auto* mm = p.get_main_module();

// add two literals to the program
auto one = mm->add_literal(1);
auto two = mm->add_literal(2);

// make the add operation between the two literals and add it to the program
mm->add_instruction(migraphx::make_op("add"), one, two);

// compile the program on the reference device
p.compile(migraphx::ref::target{});

// evaulate the program and retreive the result
auto result = p.eval({}).back();
std::cout << "add_two_literals: 1 + 2 = " << result << "\n";
```

We start by creating a simple ``` migraphx::program ``` object and then getting a pointer to the main module of it. The program is a collection of  ``` modules ``` that start executing from the main module, so instructions are added to the modules rather than directly onto the program object. We then use the ``` add_literal ``` function to add an instruction that stores the literal number ``` 1 ``` while returning an ```instruction_ref ```. The returned ``` instruction_ref ``` can be used in another instruction as an input. We use the same ``` add_literal ``` function to add a ``` 2 ``` to the program. After creating the literals, we then create the instruction to add the numbers together. This is done by using the ``` add_instruction ``` function with the ``` "add" ```  ``` operation ``` created by ``` make_op ``` along with the previou ``` add_literal ```  ``` instruction_ref ``` for the input arguments of the instruction. Finally, we can run this ``` program ``` by compiling it for the reference target (CPU) and then running it with ``` eval ```.

We can compile the program for the GPU as well, but the file will have to be moved to the  ``` test/gpu/ ``` directory and the correct target must be included:

```
#include <migraphx/gpu/target.hpp>
```

## 5.1.3 Using Parameters <a name="anotherparagraph513"></a>

The previous program will always produce the same value of adding  ``` 1 ``` and ``` 2 ```. In the next program we want to pass an input to a program and compute a value based on the input. We can modify the program to take an input parameter ``` x ```, as seen in the ``` add_parameter() ``` function:

```
migraphx::program p;
auto* mm = p.get_main_module();
migraphx::shape s{migraphx::shape::int32_type, {1}};

// add a "x" parameter with the shape s
auto x   = mm->add_parameter("x", s);
auto two = mm->add_literal(2);

// add the "add" instruction between the "x" parameter and "two" to the module
mm->add_instruction(migraphx::make_op("add"), x, two);
p.compile(migraphx::ref::target{});
```

This adds a parameter of type ``` int32 ```, and compiles it for the CPU. To run the program, we need to pass the parameter as a ``` parameter_map ``` when we call ``` eval ```. We create the ``` parameter_map ``` by setting the ``` x ``` key to an ``` argument ``` object with an ``` int ``` data type:

```
// create a parameter_map object for passing a value to the "x" parameter
std::vector<int> data = {4};
migraphx::parameter_map params;
params["x"] = migraphx::argument(s, data.data());

auto result = p.eval(params).back();
std::cout << "add_parameters: 4 + 2 = " << result << "\n";
EXPECT(result.at<int>() == 6);
```

## 5.1.4 Handling Tensor Data <a name="anotherparagraph514"></a>

In the previous examples we have only been dealing with scalars, but the ``` shape ``` class can describe multi-dimensional tensors. For example, we can compute a simple convolution:

```
migraphx::program p;
auto* mm = p.get_main_module();

// create shape objects for the input tensor and weights
migraphx::shape input_shape{migraphx::shape::float_type, {2, 3, 4, 4}};
migraphx::shape weights_shape{migraphx::shape::float_type, {3, 3, 3, 3}};

// create the parameters and add the "convolution" operation to the module
auto input   = mm->add_parameter("X", input_shape);
auto weights = mm->add_parameter("W", weights_shape);
mm->add_instruction(migraphx::make_op("convolution", {{"padding", {1, 1}}, {"stride", {2, 2}}}), input, weights);
```

Here we create two parameters for both the ``` input ``` and ``` weights ```. In the previous examples, we created simple literals, however, most programs will take data from allocated buffers (usually on the GPU). In this case, we can create ``` argument ``` objects directly from the pointers to the buffers:

```
// Compile the program
p.compile(migraphx::ref::target{});

// Allocated buffers by the user
std::vector<float> a = ...;
std::vector<float> c = ...;

// Solution vector
std::vector<float> sol = ...;

// Create the arguments in a parameter_map
migraphx::parameter_map params;
params["X"] = migraphx::argument(input_shape, a.data());
params["W"] = migraphx::argument(weights_shape, c.data());

// Evaluate and confirm the result
auto result = p.eval(params).back();
std::vector<float> results_vector(64);
result.visit([&](auto output) { results_vector.assign(output.begin(), output.end()); });

EXPECT(migraphx::verify_range(results_vector, sol));
```

An ``` argument ``` can handle memory buffers from either the GPU or the CPU. By default when running the ``` program ```, buffers are allocated on the corresponding target. When compiling for the CPU, the buffers by default will be allocated on the CPU. When compiling for the GPU, the buffers by default will be allocated on the GPU. With the option ``` offloaf_copy=true ``` set while compiling for the GPU, the buffers will be located on the CPU.

## 5.1.5 Importing From ONNX <a name="anotherparagraph515"></a>

A ``` program ``` can be built directly from an onnx file using the MIGraphX ONNX parser. This makes it easier to use neural networks directly from other frameworks. In this case, there is an ``` parse_onnx ``` function:

```
program p = migraphx::parse_onnx("model.onnx");
p.compile(migraphx::gpu::target{});
```

# 5.2 Data Types <a name="subparagraph52"></a>

## 5.2.1 Shape <a name="anotherparagraph521"></a>

```
struct migraphx::internal::shape
```

##### Public Types

```
enum type_t
```

##### Values:

```
enumerator bool_typet
```

```
enumerator half_type
```

```
enumerator float_type
```

```
enumerator double_type
```

```
enumerator uint8_type
```

```
enumerator int8_type
```

```
enumerator uint16_type
```

```
enumerator int16_type
```

```
enumerator int32_type
```

```
enumerator int64_type
```

```
enumerator uint32_type
```

```
enumerator uint64_type
```

```
enumerator tuple_type
```

##### Public Functions

```
shape()
```

```
shape(type_t t)
```

```
shape(type_t t, std::vector<std::size_t> l)
```

```
shape(type_t t, std::vector<std::size_t> l, std::vector<std::size_t> s)
```

```
template<class Range>  
inline shape(type_t t, const Range&l)
```

```
template<class Range1, class Range2>  
inline shape(type_t t, const Range1&l, const Range2&s)
```

```
shape(const std::vector<shape>&subs)
```

```
type_t type() const
```

```
const std::vector<std::size_t> &lens() const
```

```
const std::vector<std::size_t> &strides() const
```

```
std::size_t elements() const
```

```
std::size_t bytes() const
```

```
std::size_t type_size() const
```

```
std::size_t index(std::initializer_list<std::size_t> l) const
```

```
Map multiple indices to space index.
```

```
std::size_t index(const std::vector<std::size_t> &l) const
```
Map multiple indices to space index.

```
template<class Iterator>  
inline std::size_t index(Iterator start,Iterator lastconst)
```
Map multiple indices from a range of iterator to a space index.

```
std::size_t index(std::size_t i) const
```
Map element index to space index.

```
std::vector<std::size_t> multi(std::size_t i) const
```

```
void multi_copy(std::size_t i, std::size_t*start, const std::size_t*end) const
```

```
bool packed() const
```
Returns true if the shape is packed with no padding.

```
bool transposed() const
```
Returns true is the shape has been transposed. That is the strides are not in descending order

```
bool broadcasted() const
```
Returns true if the shape is broadcasting a dimension. That is, one of the strides are zero.

```
bool standard() const
```
Returns true if the shape is in its standard format. That is, the shape is both packed and not transposed.

```
bool scalar() const
```
Returns true if all strides are equal to 0 (scalar tensor)

```
shape normalize_standard() const
```

```
shape with_lens(type_t t, const std::vector<std::size_t> &l) const
```

```
shape with_lens(const std::vector<std::size_t> &l) const
```

```
template<class ...Visitors>  
inline void visit_type(Visitors... vs) const
```

```
std::string type_string() const
```

```
const std::vector<shape> &sub_shapes() const
```

##### Public Static Functions

```
static const std::vector<type_t> &types()
```

```
static std::string name(type_t t)
```

```
static std::string cpp_type(type_t t)
```

```
static shape from_permutation(type_t t, const std::vector<std::size_t> &l, const std::vector<int64_t> &perm
```

```
template<class Visitor, class TupleVisitor>  
static inline void visit(type_t t, Visitor v, TupleVisitor tv)
```

```
template<class Visitor>  
static inline void visit(type_t t,Visitor v)
```

```
template<class Visitor>  
static inline void visit_types(Visitor v)
```

```
static type_t parse_type(const std::string &s)
```

##### Friends

```
friend friend bool operator== (const shape &x, const shape &y)
```

```
friend friend bool operator!= (const shape &x, const shape &y)
```

```
friend friend std::ostream & operator<< (std::ostream &os, const shape &x)
```

```
template<class T>  
struct as
```

##### Public Types

```
using type = std::conditional_t<std::is_same<T, bool>{}, int8_t, T>
```

##### Public Functions

```
inline type max() const
```

```
inline type min() const
```

```
template<class U>
inline type operator()(U u) const
```

```
template<class U>
inline type *operator()(U *u) const
```

```
template<class U>
inline const type *operator()(const U *u) const
```

```
inline type operator()() const
```

```
inline std::size_t size(std::size_t n = 1) const
```

```
template<class U>
inline type *from(U *buffer, std::size_t n = 0) const
```

```
template<class U>
inline const type *from(const U *buffer, std::size_t n = 0) const
```

```
inline type_t type_enum() const
```

```
template<class T, class = void>
struct get_type
```

```
template<class T>
struct get_type<bool, T> : public std::integral_constant<type_t, bool_type>
```

```
template<class T>
struct get_type<const T> : public migraphx::internal::shape::get_type<T>
```

```
template<class T>
struct get_type<double, T> : public std::integral_constant<type_t, double_type>
```

```
template<class T>
struct get_type<float, T> : public std::integral_constant<type_t, float_type>
```

```
template<class T>
struct get_type<half, T> : public std::integral_constant<type_t, half_type>
```

```
template<class T>
struct get_type<int16_t, T> : public std::integral_constant<type_t, int16_type>
```

```
template<class T>
struct get_type<int32_t, T> : public std::integral_constant<type_t, int32_type>
```

```
template<class T>
struct get_type<int64_t, T> : public std::integral_constant<type_t, int64_type>
```

```
template<class T>
struct get_type<int8_t, T> : public std::integral_constant<type_t, int8_type>
```

```
template<class T>
struct get_type<uint16_t, T> : public std::integral_constant<type_t, uint16_type>
```

```
template<class T>
struct get_type<uint32_t, T> : public std::integral_constant<type_t, uint32_type>
```

```
template<class T>
struct get_type<uint64_t, T> : public std::integral_constant<type_t, uint64_type>
```

```
template<class T>
struct get_type<uint8_t, T> : public std::integral_constant<type_t, uint8_type>
```

## 5.2.2 Literal <a name="anotherparagraph522"></a>

```
struct migraphx::internal::literal : public migraphx::internal::raw_data<literal>
```
Represents a raw literal.
This stores the literal has a raw buffer that is owned by this class

##### Public Functions

```
inline literal()
```

```
template<class U, class T = deduce<U>, shape::type_t ShapeType = shape::get_type<T>{}>
inline literal(U x)
```

```
template<class T>
inline literal(const shape &s, const std::vector<T> &x)
```

```
template<class T>
inline literal(const shape &s, const std::initializer_list<T> &x)
```

```
template<class Iterator>
inline literal(const shape &s, Iterator start, Iterator end)
```

```
template<class T, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<sizeof(T) == 1>{})), int>::type = 0>
inline literal(const shape &s, T *x)
```

```
inline bool empty() const
```
Whether data is available.

```
inline const char *data() const
```
Provides a raw pointer to the data.

```
inline const shape &get_shape() const
```

```
inline std::vector<literal> get_sub_objects() const
```

```
inline argument get_argument() const
```
Convert the data to an argument.

## 5.2.3 Argument <a name="anotherparagraph523"></a>

```
struct migraphx::internal::argument : public migraphx::internal::raw_data<argument>
```
Arguments passed to instructions.
An ``` argument ``` can represent a raw buffer of data that either be referenced from another element or it can be owned by the argument.

##### Public Functions

```
argument() = default
```

```
argument(const shape &s)
```

```
template<class F, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<std::is_pointer<decltype(std::declval<F>()())>{}>{})), int>::type = 0>
inline argument(shape s, F d)
```

```
template<class T>
inline argument(shape s, T *d)
```

```
template<class T>
inline argument(shape s, std::shared_ptr<T> d)
```

```
argument(shape s, std::nullptr_t)
```

```
argument(const std::vector<argument> &args)
```

```
char *data() const
```
Provides a raw pointer to the data.


```
bool empty() const
```
Whether data is available.

```
const shape &get_shape() const
```

```
argument reshape(const shape &s) const
```

```
argument copy() const
```

```
argument share() const
```
Make copy of the argument that is always sharing the data.

```
std::vector<argument> get_sub_objects() const
```

```
argument element(std::size_t i) const
```
Return the ith element.

## 5.2.4 raw_data <a name="anotherparagraph524"></a>

```
template<class Derived>
struct migraphx::internal::raw_data : public migraphx::internal::raw_data_base
```
Provides a base class for common operations with raw buffer.

For classes that handle a raw buffer of data, this will provide common operations such as equals, printing, and visitors. To use this class the derived class needs to provide a ``` data() ``` method to retrieve a raw pointer to the data, and ``` get_shape ``` method that provides the shape of the data.

##### Public Functions

```
template<class Visitor>
inline void visit_at(Visitor v, std::size_t n = 0) const
```
Visits a single data element at a certain index.

##### Parameters
- v – A function which will be called with the type of data

- n – The index to read from

```
template<class Visitor, class TupleVisitor>
inline void visit(Visitor v, TupleVisitor tv) const
```

```
template<class Visitor>
inline void visit(Visitor v) const
```
Visits the data.
This will call the visitor function with a ``` tensor_view<T> ``` based on the shape of the data.

##### Parameters:
-  v – A function to be called with ``` tensor_view<T> ```

```
inline bool single() const
```
Returns true if the raw data is only one element.

```
template<class T>
inline T at(std::size_t n = 0) const
```
Retrieves a single element of data.

- Parameters            n – The index to retrieve the data from
- Template Parameters   T – The type of data to be retrieved
- Returns               The element as T

```
inline auto_cast implicit() const
```
Implicit conversion of raw data pointer.

```
template<class T>
inline tensor_view<T> get() const
```
Get a tensor_view to the data.

```
template<class T>
inline T *cast() const
```
Cast the data pointer.

```
inline std::string to_string() const
```

##### Friends

```
template<class Stream> inline friend friend Stream & operator<< (Stream &os, const Derived &d)
```

```
struct auto_cast
```
##### Public Types

```
using is_data_ptr = bool_c<(std::is_void<T>{} or std::is_same<char, std::remove_cv_t<T>>{} or std::is_same<unsigned char, std::remove_cv_t<T>>{})>
```

```
using get_data_type = std::conditional_t<is_data_ptr<T>{}, float, T>
```
##### Public Functions

```
template<class T>
inline operator T()
```

```
template<class T>
inline bool matches() const
```

```
template<class T>
inline operator T*()
```

```
template<class T>
inline bool matches() const
```

```
template<class T>
inline operator T*()
```
##### Public Members

```
const Derived *self
```

## 5.2.5 Tensor_view <a name="anotherparagraph525"></a>

```
template<class T>
struct migraphx::internal::tensor_view
```

##### Public Types

```
using value_type = T
```

```
using iterator = basic_iota_iterator<tensor_view_iterator_read<tensor_view<T>>, std::size_t>
```

```
using const_iterator = basic_iota_iterator<tensor_view_iterator_read<const tensor_view<T>>, std::size_t>
```

##### Public Functions

```
inline tensor_view()
```

```
inline tensor_view(shape s, T *d)
```

```
inline const shape &get_shape() const
```

```
inline bool empty() const
```

```
inline std::size_t size() const
```

```
inline T *data()
```

```
inline const T *data() const
```

```
template<class ...Ts, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<std::is_integral<Ts>{}...>{})), int>::type = 0>
inline const T &operator()(Ts... xs) const
```

```
template<class ...Ts, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<std::is_integral<Ts>{}...>{})), int>::type = 0>
inline T &operator()(Ts... xs)
```

```
template<class Iterator, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<not std::is_integral<Iterator>{}>{})), int>::type = 0>
inline const T &operator()(Iterator start, Iterator last) const
```

```
template<class Iterator, long PrivateRequires__LINE__ = __LINE__, typename std::enable_if<(PrivateRequires__LINE__ == __LINE__ && (migraphx::and_<not std::is_integral<Iterator>{}>{})), int>::type = 0>
inline T &operator()(Iterator start, Iterator last)
```

```
inline T &operator[](std::size_t i)
```

```
inline const T &operator[](std::size_t i) const
```

```
inline T &front()
```

```
inline const T &front() const
```

```
inline T &back()
```

```
inline const T &back() const
```

```
inline iterator begin()
```

```
inline iterator end()
```

```
inline const_iterator begin() const
```

```
inline const_iterator end() const
```

```
template<class U = T>
inline std::vector<U> to_vector() const
```

##### Friends

```
inline friend friend std::ostream & operator<< (std::ostream &os, const tensor_view< T > &x)
```

# 5.3 Program <a name="subparagraph53"></a>

## 5.3.1 Instruction <a name="anotherparagraph531"></a>

```
**struct migraphx::internal::instruction**[https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/dev/program.html\#_CPPv4N8migraphx8internal11instructionE](https://rocmsoftwareplatform.github.io/AMDMIGraphX/doc/html/dev/program.html#_CPPv4N8migraphx8internal11instructionE)
```

##### Public Functions

```
inline instruction()
```

```
instruction(operation o, shape r, std::vector<instruction_ref> args)
```

```
instruction(operation o, shape r, std::vector<instruction_ref> args, std::vector<module_ref> modules)
```

```
instruction(literal l)
```

```
void replace(operation o)
```

```
void recompute_shape()
```

```
void clear_arguments()
```

```
bool valid(instruction_ref start, bool check_order = false) const
```

```
bool valid() const
```

```
shape get_shape() const
```

```
const literal &get_literal() const
```

```
const operation &get_operator() const
```

```
std::string name() const
```

```
const std::vector<instruction_ref> &inputs() const
```

```
const std::vector<module_ref> &module_inputs() const
```

```
const std::vector<instruction_ref> &outputs() const
```

```
void add_output(instruction_ref ins)
```

```
template<class T>
inline void remove_output(const T &ins)
```

```
bool can_eval() const
```

```
argument eval(bool check_eval = true) const
```

```
void finalize(context &ctx)
```

```
void set_normalized(bool value = true)
```

```
bool is_normalized() const
```

```
bool need_normalization() const
```

```
operation normalized_operator() const
```

```
void debug_print() const
```

##### Public Static Functions

```
static void replace_refs(instruction_ref ins, const std::unordered_map<instruction_ref, instruction_ref> &map_insts, const std::unordered_map<module_ref, module_ref> &map_mods)
```

```
static void backreference(instruction_ref ref)
```

```
static void replace_argument(instruction_ref ins, instruction_ref old, instruction_ref new_ins)
```

```
static void replace_mod_argument(instruction_ref ins, module_ref old, module_ref new_mod)
```

```
static void replace(instruction_ref ins, operation o, const shape &r, std::vector<instruction_ref> args)
```

```
static void replace(instruction_ref ins, operation o, const shape &r, std::vector<instruction_ref> args, std::vector<module_ref> module_args)
```

```
static instruction_ref get_output_alias(instruction_ref ins, bool shallow = false)
```

```
static void print(std::ostream &os, instruction_ref ins, const std::unordered_map<instruction_ref, std::string> &names)
```

##### Friends

```
friend friend bool operator== (const instruction &i, instruction_ref ref)
```

```
friend friend bool operator== (const instruction &x, const instruction &y)
```

```
friend friend bool operator!= (const instruction &x, const instruction &y)
```

```
friend friend bool operator== (instruction_ref ref, const instruction &i)
```

```
friend friend bool operator!= (const instruction &i, instruction_ref ref)
```

```
friend friend bool operator!= (instruction_ref ref, const instruction &i)
```

## 5.3.2 Instruction_ref <a name="anotherparagraph532"></a>

```
type migraphx::internal::instruction_ref
```
References an instruction in the program.

## 5.3.3 Program <a name="anotherparagraph533"></a>

```
struct migraphx::internal::program
```
Stores the instruction stream.

##### Public Functions

```
program()
```

```
program(program&&) noexcept
```

```
program(const program&)
```

```
program &operator=(program)
```

```
program() noexcept
```

```
std::vector<std::string> get_parameter_names() const
```

```
shape get_parameter_shape(std::string name) const
```

```
instruction_ref get_parameter(std::string name) const
```

```
std::unordered_map<std::string, shape> get_parameter_shapes() const
```

```
std::vector<argument> eval(parameter_map params) const
```

```
std::size_t size() const
```

```
std::vector<shape> get_output_shapes() const
```

```
context &get_context() const
```

```
instruction_ref validate() const
```

```
void compile(const target &t, compile_options options = compile_options{})
```

```
bool is_compiled() const
```

```
void finalize()
```

```
void perf_report(std::ostream &os, std::size_t n, parameter_map params, std::size_t batch = 1) const
```

```
void mark(const parameter_map &params, marker &&m)
```

```
value to_value() const
```

```
void from_value(const value &v)
```

```
void debug_print() const
```

```
void debug_print(instruction_ref ins) const
```

```
void print(std::unordered_map<instruction_ref, std::string> &names, const std::function<void(instruction_ref, std::unordered_map<instruction_ref, std::string>)> &print_func) const
```

```
void print_graph(std::ostream &os, bool brief = false) const
```

```
void print_cpp(std::ostream &os) const
```

```
void dry_run(parameter_map params) const
```

```
void annotate(std::ostream &os, const std::function<void(instruction_ref)> &a) const
```

```
program &sort()
```

```
module *create_module(const std::string &name)
```

```
module *get_module(const std::string &name)
```

```
const module *get_module(const std::string &name) const
```

```
module *get_main_module()
```

```
const module *get_main_module() const
```

```
std::vector<const module*> get_modules() const
```

```
std::vector<module*> get_modules()
```

```
void remove_module(const std::string &name)
```

```
void remove_unused_modules()
```

###### Friends

```
friend friend std::ostream & operator<< (std::ostream &os, const program &p)
```

```
friend friend bool operator== (const program &x, const program &y)
```

```
inline friend friend bool operator!= (const program &x, const program &y)
```

## 5.3.4 Parse_onnx <a name="anotherparagraph534"></a>

```
program migraphx::internal::parse_onnx(const std::string &name, const onnx_options& = onnx_options{})
```
Create a program from an onnx file.

## 5.3.5 Parse_tf <a name="anotherparagraph535"></a>

```
program migraphx::internal::parse_tf(const std::string &name, const tf_options &options = tf_options{})
```
Create a program from a tf pb file (default is nhwc format)

## 5.3.6 Onnx_options <a name="anotherparagraph536"></a>

```
struct migraphx::internal::onnx_options
```
struct to pass in onnx options to parser

##### Public Members

```
std::size_t default_dim_value = 1
```
default batch size to use (if not specified in onnx file)

```
std::unordered_map<std::string, std::vector<std::size_t>> map_input_dims = {}
```
Explicitly specify the dims of an input.

```
bool skip_unknown_operators = false
```
Continue parsing onnx file if an unknown operator is found.

```
bool print_program_on_error = false
```
Print program if an error occurs.

```
int64_t max_loop_iterations = 10
```
Max iter num for the loop operator.

## 5.3.7 Tf_options <a name="anotherparagraph537"></a>

```
struct migraphx::internal::tf_options
```
struct to pass in tf options to parser

##### Public Members

```
bool is_nhwc = false
```

```
unsigned int batch_size = 1
```

```
std::unordered_map<std::string, std::vector<std::size_t>> map_input_dims = {}
```
Explicitly specify the dims of an input.

```
std::vector<std::string> output_node_names = {}
```

# 5.4 Targets <a name="subparagraph54"></a>

## 5.4.1 Target <a name="anotherparagraph541"></a>

```
struct migraphx::internal::target
```
An interface for a compilation target.

##### Public Functions

```
std::string name() const
```
A unique name used to identify the target.

```
std::vector<pass> get_passes(context &ctx, const compile_options &options) const
```
The transformation pass to be run during compilation.

##### Parameters

-   ctx – This is the target-dependent context that is created by ``` get_context ```
-   options – Compiling options passed in by the user

##### Returns: The passes to be ran

```
context get_context() const
```
Construct a context for the target.

##### Returns: The context to be used during compilation and execution.

```
argument copy_to(const argument &arg) const
```
copy an argument to the current target.

##### Parameters

-   arg – Input argument to be copied to the target

-   Returns: Argument in the target.

```
argument copy_from(const argument &arg) const
```
copy an argument from the current target.

##### Parameters: 

-   arg – Input argument to be copied from the target

-   Returns: Argument in the host.

```
argument allocate(const shape &s) const
```
Allocate an argument based on the input shape.

##### Parameters: 

-   s – Shape of the argument to be allocated in the target

-   Returns: Allocated argument in the target.

## 5.4.2 gpu::target <a name="anotherparagraph542"></a>

```
struct migraphx::internal::gpu::target
```

##### Public Functions

```
std::string name() const
```

```
std::vector<pass> get_passes(migraphx::context &gctx, const compile_options &options) const
```

```
migraphx::context get_context() const
```

```
argument copy_to(const argument&arg) const
```

```
argument copy_from(const argument &arg) const
```

```
argument allocate(const shape &s) const
```

## 5.4.3 cpu::target <a name="anotherparagraph543"></a>

```
struct migraphx::internal::cpu::target
```

##### Public Functions

```
std::string name() const
```

```
std::vector<pass> get_passes(migraphx::context &gctx, const compile_options&) const
```

```
inline migraphx::context get_context() const
```

```
inline argument copy_to(const argument &arg) const
```

```
inline argument copy_from(const argument &arg) const
```

```
argument allocate(const shape &s) const
```

# 5.5 Passes <a name="subparagraph55"></a>

## 5.5.1 Pass <a name="anotherparagraph551"></a>

```
struct migraphx::internal::pass
```
An interface for applying a transformation to the instructions in a ``` program ```

##### Public Functions

```
std::string name() const
```
A unique name used to identify the pass.

```
void apply(module_pass_manager \&mpm) const
```
Run the pass on the module.

```
void apply(module \&m)const
```

```
void apply(program&p)const
```
Run the pass on the program.

## 5.5.2 Dead_code_elimination <a name="anotherparagraph552"></a>

```
struct migraphx::internal::dead_code_elimination
```
Remove instructions where the output is not used.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &m) const
```

```
void apply(program &p) const
```

## 5.5.3 Eliminate_common_subexpression <a name="anotherparagraph553"></a>

```
struct migraphx::internal::eliminate_common_subexpression
```
Remove identical instructions.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module \&p) const
```

## 5.5.4 Eliminate_concat <a name="anotherparagraph554"></a>

```
struct migraphx::internal::eliminate_concat
```
Remove concat operators by having each operator can write to different chunk of memory.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module \&p) const
```

##### Public Members

```
concat_optimization concat_opt
```

## 5.5.5 Eliminate_contiguous <a name="anotherparagraph555"></a>

```
struct migraphx::internal::eliminate_contiguous
```
Remove contiguous instructions by checking if the operator can use non-standard shapes.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

##### Public Members

```
std::string op_name
```

## 5.5.6 Eliminate_identity <a name="anotherparagraph556"></a>

```
struct migraphx::internal::eliminate_identity
```
Remove identity instructions. Currently when used as the last pass, it will preserve the semantics of previous program state, therefore dead code elimination should not be used afterwards.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

## 5.5.7 Eliminate_pad <a name="anotherparagraph557"></a>

```
struct migraphx::internal::eliminate_pad
```
Remove pads if they can be written as an attribute to another op (im2col, convolution, pooling)

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &m) const
```

## 5.5.8 Propagate_constant <a name="anotherparagraph558"></a>

```
struct migraphx::internal::propagate_constant
```
Replace instructions which take all literals with a literal of the computation.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

## 5.5.9 Rewrite_batchnorm <a name="anotherparagraph559"></a>

```
struct migraphx::internal::rewrite_batchnorm
```
Rewrite batchnorm to a multiply and add.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

## 5.5.10 Rewrite_rnn <a name="anotherparagraph5510"></a>

```
struct migraphx::internal::rewrite_rnn
```
Rewrite rnn to gemm and add.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &prog) const
```

## 5.5.11 Schedule <a name="anotherparagraph5511"></a>

```
struct migraphx::internal::schedule
```
Schedule instructions for concurrent execution

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

##### Public Members

```
schedule_model model = {}
```

```
bool enable = true
```

## 5.5.12 Simplify_algebra <a name="anotherparagraph5512"></a>

```
struct migraphx::internal::simplify_algebra
```
Simplify many algebraic instructions to more efficient versions.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

## 5.5.13 Simplify_reshapes <a name="anotherparagraph5513"></a>

```
struct migraphx::internal::simplify_reshapes
```
Eliminate redundant reshapes.

##### Public Functions

```
inline std::string name() const
```

```
void apply(module &p) const
```

# 5.6 Matchers <a name="subparagraph56"></a>

## 5.6.1 Introduction <a name="anotherparagraph561"></a>

The matchers provide a way compose several predicates together. Many of the matchers can be composed so that ``` m(m1, m2) ``` will first check that ``` m ``` matches and then it will check that ``` m1 ``` and ``` m2 ``` will match.

The most commonly-used matcher is the ``` name ``` matcher. It will match the instruction that have the operator that is equal to the name specified:

```
auto match_sum = name("sum");
```

This will find ``` sum ``` operators. We can also find ``` sum ``` operators which the output is ``` standard_shape ```:

auto match_sum = name(“sum”)(standard_shape());

## 5.6.2 Arguments <a name="anotherparagraph562"></a>

We also want to match arguments to the instructions as well. One way, is to match each argument using the ``` arg ``` matcher:

```
auto match_sum = name("sum")(arg(0)(name("@literal"), arg(1)(name("@literal"))));
```

This will match a ``` sum ``` operator with the two arguments that are literals. Of course, instead of writing ``` arg(0) ``` and ``` arg(1) ``` everytime, the ``` args ``` matcher can be used:

```
auto match_sum = name("sum")(args(name("@literal"), name("@literal")));
```

## 5.6.3 Binding <a name="anotherparagraph563"></a>

As we traverse through the instructions we may want reference some of the instructions we find along the way. We can do this by calling ``` .bind ```:

```
auto match_sum = name("sum")(args(
			name("@literal").bind("one"),
			name("@literal").bind("two")
		)).bind("sum");
```

This will associate the instruction to a name that can be read from the ``` matcher_result ``` when it matches.

## 5.6.4 Finding matches <a name="anotherparagraph564"></a>

Finally, when you want to use the matchers to find instructions a callback object can be written which has the matcher and an ``` apply ``` function which will take the ``` matcher_result ``` when the match is found:

```
struct match_find_sum
{

	auto matcher() const { return name("sum"); }

	void apply(program& p, matcher_result r) const
	{
		// Do something with the result
	}
};

find_matches(prog, match_find_sum{});
```

## 5.6.5 Creating matchers <a name="anotherparagraph565"></a>

There are several ways to create matchers. The macros ``` MIGRAPH_BASIC_MATCHER ``` and ``` MIGRAPH_PRED_MATCHER ``` help with creating matchers. For example, we can create a matcher for shapes that are broadcasted:

```
MIGRAPH_PRED_MATCHER(broadcasted_shape, instruction_ref ins)
{
	return ins-\>get_shape().broadcasted();
}
```

If we want parameters to the predicate, then we will need to use the ``` make_basic_pred_matcher ``` to create the matcher. For example, here is how we would create a matcher to check the number of dimensions of the shape:

```
inline auto number_of_dims(std::size_t n)
{
	return make_basic_pred_matcher([=](instruction_ref ins) {
	    return ins-\>get_shape().lens().size() == n;

	});
}
```

# 5.7 Tools <a name="subparagraph57"></a>

## 5.7.1 roctx.py <a name="anotherparagraph571"></a>

MIGraphX driver provides ``` roctx ``` command which can be used with ``` rocprof ``` binary to get marker timing information for each MIGraphX operator. In order to help user to process timing information, rocTX helper script is provided at ``` tools/roctx.py ```. The ``` roctx.py ``` helper script provides two main functionality: ``` run ``` and ``` parse ```. Available knobs and usage are given below:

```
Usage: roctx.py [-h] [--json-path json_path] [--out out]
[--study-name study-name] [--repeat repeat] [--parse]
[--run run] [--debug]
```

```
--run
```
Runs ``` migraphx-driver roctx ``` command and given ``` migraphx-driver ``` knobs, and then parses the results, providing GPU kernel timing information. MIGraphX knobs can be given via a string to ``` --run ``` knob. Please see the examples below.

```
--parse
```
Given ``` --json-path ```, parses JSON file and provides GPU kernel timing information.

```
--out
```
Output folder

```
--study-name
```
Optional. Allows user to name a study for easier interpretation. Defaults to timestamp.

```
--repeat
```
Number of iterations. Set to 2 by default.

```
--debug
```
Provides additional debug information related to data. Only use for debugging purposes.

##### Examples:

##### Running inference with rocTX for a given ONNX file:

```
python roctx.py --run '--onnx --gpu fcn-resnet50-11.onnx' --out output_folder --repeat 5
```
After a run, similar to output given below is expected at terminal. The output will provide ``` SUM ```, ``` MIN ```, ``` MAX ``` and ``` COUNT ``` information for each kernel executed for a given model. Average total time is also provided. There are three files provided for reference:

1. ``` OUTPUT CSV FILE ``` provides a summary of the run, providing utilized MIGraphX knobs and related kernel timing information

2. ``` KERNEL TIMING DETAILS ``` provides the hotspot kernel timing information

3. This will provide all output data related to all iterations executed during a run.

Parsing an already existing JSON file:

```
python roctx.py --parse --json-path ../trace.json
```
