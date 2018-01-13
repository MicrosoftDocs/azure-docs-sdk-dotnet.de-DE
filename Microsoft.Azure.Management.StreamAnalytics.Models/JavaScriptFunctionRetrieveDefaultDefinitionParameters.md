<Type Name="JavaScriptFunctionRetrieveDefaultDefinitionParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters">
  <TypeSignature Language="C#" Value="public class JavaScriptFunctionRetrieveDefaultDefinitionParameters : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JavaScriptFunctionRetrieveDefaultDefinitionParameters extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class JavaScriptFunctionRetrieveDefaultDefinitionParameters&#xA;Inherits FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="F#" Value="type JavaScriptFunctionRetrieveDefaultDefinitionParameters = class&#xA;    inherit FunctionRetrieveDefaultDefinitionParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters</BaseTypeName>
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
            Die Parameter benötigt, um die Standarddefinition der Funktion für eine JavaScript-Funktion abzurufen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionRetrieveDefaultDefinitionParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JavaScriptFunctionRetrieveDefaultDefinitionParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JavaScriptFunctionRetrieveDefaultDefinitionParameters (string script = null, Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.StreamAnalytics.Models.UdfType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional script As String = null, Optional udfType As Nullable(Of UdfType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters : string * Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters (script, udfType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="udfType" Type="System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;" />
      </Parameters>
      <Docs>
        <param name="script">Der JavaScript-Code, die eine einzelne Funktion-Definition enthält. Zum Beispiel: ' Function (X, y) {Return X + y;} ".</param>
        <param name="udfType">Der Funktionstyp. Folgende Werte sind möglich: "Scalar"</param>
        <summary>
            Initialisiert eine neue Instanz der JavaScriptFunctionRetrieveDefaultDefinitionParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.script")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest, die eine einzelne Funktion-Definition enthält JavaScript-Code. Zum Beispiel: ' Function (X, y) {Return X + y;} ".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UdfType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberSignature Language="VB.NET" Value="Public Property UdfType As Nullable(Of UdfType)" />
      <MemberSignature Language="F#" Value="member this.UdfType : Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.JavaScriptFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.udfType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Funktion. Folgende Werte sind möglich: "Scalar"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>