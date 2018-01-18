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
            <span data-ttu-id="6b9e6-101">Text der Fehlerantwort zurückgegeben von der API.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-101">Body of the error response returned from the API.</span></span>
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
            <span data-ttu-id="6b9e6-102">Initialisiert eine neue Instanz der ErrorEntity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-102">Initializes a new instance of the ErrorEntity class.</span></span>
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
        <param name="extendedCode"><span data-ttu-id="6b9e6-103">Fehlertyp.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-103">Type of error.</span></span></param>
        <param name="messageTemplate"><span data-ttu-id="6b9e6-104">Nachrichtenvorlage.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-104">Message template.</span></span></param>
        <param name="parameters"><span data-ttu-id="6b9e6-105">Parameter für die Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-105">Parameters for the template.</span></span></param>
        <param name="innerErrors"><span data-ttu-id="6b9e6-106">In den internen Fehlern.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-106">Inner errors.</span></span></param>
        <param name="code"><span data-ttu-id="6b9e6-107">Grundlegende Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-107">Basic error code.</span></span></param>
        <param name="message"><span data-ttu-id="6b9e6-108">Alle Details des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-108">Any details of the error.</span></span></param>
        <summary>
            <span data-ttu-id="6b9e6-109">Initialisiert eine neue Instanz der ErrorEntity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-109">Initializes a new instance of the ErrorEntity class.</span></span>
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
            <span data-ttu-id="6b9e6-110">Ermittelt oder definiert grundlegende Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-110">Gets or sets basic error code.</span></span>
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
            <span data-ttu-id="6b9e6-111">Ruft ab oder legt ihn fest Fehler.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-111">Gets or sets type of error.</span></span>
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
            <span data-ttu-id="6b9e6-112">Ruft ab oder legt den interne Fehlern.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-112">Gets or sets inner errors.</span></span>
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
            <span data-ttu-id="6b9e6-113">Ruft ab oder legt alle Details des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-113">Gets or sets any details of the error.</span></span>
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
            <span data-ttu-id="6b9e6-114">Ruft ab, oder legt ihn fest Nachrichtenvorlage.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-114">Gets or sets message template.</span></span>
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
            <span data-ttu-id="6b9e6-115">Ruft ab oder legt Parameter für die Vorlage fest.</span><span class="sxs-lookup"><span data-stu-id="6b9e6-115">Gets or sets parameters for the template.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>