<Type Name="AnalyzeRequest" FullName="Microsoft.Azure.Search.Models.AnalyzeRequest">
  <TypeSignature Language="C#" Value="public class AnalyzeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AnalyzeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AnalyzeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class AnalyzeRequest" />
  <TypeSignature Language="F#" Value="type AnalyzeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt an, Text und Analyse Komponenten verwendet, um diesen Text in Tokens zu Zerteilen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AnalyzeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest (string text, Microsoft.Azure.Search.Models.AnalyzerName analyzer = null, Microsoft.Azure.Search.Models.TokenizerName tokenizer = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string text, class Microsoft.Azure.Search.Models.AnalyzerName analyzer, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor(System.String,Microsoft.Azure.Search.Models.AnalyzerName,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (text As String, Optional analyzer As AnalyzerName = null, Optional tokenizer As TokenizerName = null, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AnalyzeRequest : string * Microsoft.Azure.Search.Models.AnalyzerName * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.AnalyzeRequest" Usage="new Microsoft.Azure.Search.Models.AnalyzeRequest (text, analyzer, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="analyzer" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="text">Der Text in Tokens zu Zerteilen.</param>
        <param name="analyzer">Der Name des Analyzers verwenden, um zu dem angegebenen Text. Wenn dieser Parameter nicht angegeben wird, müssen Sie stattdessen einen Tokenizer angeben. Der Tokenizer und Analyzer-Parameter schließen sich gegenseitig aus.</param>
        <param name="tokenizer">Der Name des tokenizers zu verwenden, um zu dem angegebenen Text. Wenn dieser Parameter nicht angegeben wird, müssen Sie stattdessen einen Analyzer angeben. Der Tokenizer und Analyzer-Parameter schließen sich gegenseitig aus.</param>
        <param name="tokenFilters">Eine optionale Liste der token Filter verwenden, wenn den angegebenen Text zu unterbrechen. Dieser Parameter kann nur festgelegt werden, wenn den Tokenizer-Parameter verwenden.</param>
        <param name="charFilters">Eine optionale Liste der Filter Zeichen verwenden, wenn den angegebenen Text zu unterbrechen. Dieser Parameter kann nur festgelegt werden, wenn den Tokenizer-Parameter verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der AnalyzeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName Analyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName Analyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.Analyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="analyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Analyzers verwenden, um zu dem angegebenen Text. Wenn dieser Parameter nicht angegeben wird, müssen Sie stattdessen einen Tokenizer angeben. Der Tokenizer und Analyzer-Parameter schließen sich gegenseitig aus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="charFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine optionale Liste von Zeichen verwenden, wenn den angegebenen Text wichtige Filter. Dieser Parameter kann nur festgelegt werden, wenn den Tokenizer-Parameter verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Text in Tokens zu Zerteilen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine optionale Liste mit token Filter zu verwenden, wenn den angegebenen Text wichtige. Dieser Parameter kann nur festgelegt werden, wenn den Tokenizer-Parameter verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des tokenizers zu verwenden, um zu dem angegebenen Text. Wenn dieser Parameter nicht angegeben wird, müssen Sie stattdessen einen Analyzer angeben. Der Tokenizer und Analyzer-Parameter schließen sich gegenseitig aus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="analyzeRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>