<Type Name="JavaScriptFunctionBinding" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding">
  <TypeSignature Language="C#" Value="public class JavaScriptFunctionBinding : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JavaScriptFunctionBinding extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class JavaScriptFunctionBinding&#xA;Inherits FunctionBinding" />
  <TypeSignature Language="F#" Value="type JavaScriptFunctionBinding = class&#xA;    inherit FunctionBinding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.StreamAnalytics/JavascriptUdf")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Bindung an eine JavaScript-Funktion.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JavaScriptFunctionBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionBinding (string script = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional script As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding script" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="script">Der JavaScript-Code, die eine einzelne Funktion-Definition enthält. Zum Beispiel: ' Function (X, y) {Return X + y;} "</param>
        <summary>
            Initialisiert eine neue Instanz der JavaScriptFunctionBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionBinding.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest, die eine einzelne Funktion-Definition enthält JavaScript-Code. Zum Beispiel: ' Function (X, y) {Return X + y;} "
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>