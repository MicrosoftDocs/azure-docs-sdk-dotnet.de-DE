<Type Name="ErrorEntity" FullName="Microsoft.Azure.Management.WebSites.Models.ErrorEntity">
  <TypeSignature Language="C#" Value="public class ErrorEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ErrorEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorEntity" />
  <TypeSignature Language="F#" Value="type ErrorEntity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Text der Fehlerantwort zurückgegeben von der API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ErrorEntity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorEntity (string extendedCode = null, string messageTemplate = null, System.Collections.Generic.IList&lt;string&gt; parameters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; innerErrors = null, string code = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string extendedCode, string messageTemplate, class System.Collections.Generic.IList`1&lt;string&gt; parameters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; innerErrors, string code, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ErrorEntity},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional extendedCode As String = null, Optional messageTemplate As String = null, Optional parameters As IList(Of String) = null, Optional innerErrors As IList(Of ErrorEntity) = null, Optional code As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ErrorEntity : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.ErrorEntity" Usage="new Microsoft.Azure.Management.WebSites.Models.ErrorEntity (extendedCode, messageTemplate, parameters, innerErrors, code, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="extendedCode" Type="System.String" />
        <Parameter Name="messageTemplate" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="innerErrors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt;" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extendedCode">Fehlertyp.</param>
        <param name="messageTemplate">Nachrichtenvorlage.</param>
        <param name="parameters">Parameter für die Vorlage.</param>
        <param name="innerErrors">In den internen Fehlern.</param>
        <param name="code">Grundlegende Fehlercode.</param>
        <param name="message">Alle Details des Fehlers.</param>
        <summary>
            Initialisiert eine neue Instanz der ErrorEntity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert grundlegende Fehlercode.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedCode">
      <MemberSignature Language="C#" Value="public string ExtendedCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtendedCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.ExtendedCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedCode As String" />
      <MemberSignature Language="F#" Value="member this.ExtendedCode : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.ExtendedCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Fehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerErrors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; InnerErrors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; InnerErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.InnerErrors" />
      <MemberSignature Language="VB.NET" Value="Public Property InnerErrors As IList(Of ErrorEntity)" />
      <MemberSignature Language="F#" Value="member this.InnerErrors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.InnerErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innerErrors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ErrorEntity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den interne Fehlern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt alle Details des Fehlers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTemplate">
      <MemberSignature Language="C#" Value="public string MessageTemplate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageTemplate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.MessageTemplate" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageTemplate As String" />
      <MemberSignature Language="F#" Value="member this.MessageTemplate : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.MessageTemplate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messageTemplate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Nachrichtenvorlage.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ErrorEntity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Parameter für die Vorlage fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>