<Type Name="ErrorDetail" FullName="Microsoft.Azure.OperationalInsights.Models.ErrorDetail">
  <TypeSignature Language="C#" Value="public class ErrorDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.Models.ErrorDetail" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorDetail" />
  <TypeSignature Language="F#" Value="type ErrorDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eec65-101">Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="eec65-101">Error details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eec65-102">Initialisiert eine neue Instanz der Klasse "errordetail".</span><span class="sxs-lookup"><span data-stu-id="eec65-102">Initializes a new instance of the ErrorDetail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetail (string code, string message, string target = null, string value = null, System.Collections.Generic.IList&lt;string&gt; resources = null, object additionalProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, string value, class System.Collections.Generic.IList`1&lt;string&gt; resources, object additionalProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional target As String = null, Optional value As String = null, Optional resources As IList(Of String) = null, Optional additionalProperties As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.ErrorDetail : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * obj -&gt; Microsoft.Azure.OperationalInsights.Models.ErrorDetail" Usage="new Microsoft.Azure.OperationalInsights.Models.ErrorDetail (code, message, target, value, resources, additionalProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="additionalProperties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="eec65-103">Der Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="eec65-103">The error's code.</span></span></param>
        <param name="message"><span data-ttu-id="eec65-104">Interaktive Workflowdienste-lesbare Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="eec65-104">A human readable error message.</span></span></param>
        <param name="target"><span data-ttu-id="eec65-105">Gibt an, welche Eigenschaft in der Anforderung für den Fehler verantwortlich ist.</span><span class="sxs-lookup"><span data-stu-id="eec65-105">Indicates which property in the request is responsible for the error.</span></span></param>
        <param name="value"><span data-ttu-id="eec65-106">Gibt an, welcher Wert in 'Target' für den Fehler verantwortlich ist.</span><span class="sxs-lookup"><span data-stu-id="eec65-106">Indicates which value in 'target' is responsible for the error.</span></span></param>
        <param name="resources"><span data-ttu-id="eec65-107">Gibt an, Ressourcen, die für den Fehler verantwortlich sind.</span><span class="sxs-lookup"><span data-stu-id="eec65-107">Indicates resources which were responsible for the error.</span></span></param>
        <param name="additionalProperties">To be added.</param>
        <summary>
            <span data-ttu-id="eec65-108">Initialisiert eine neue Instanz der Klasse "errordetail".</span><span class="sxs-lookup"><span data-stu-id="eec65-108">Initializes a new instance of the ErrorDetail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public object AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : obj with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="additionalProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="eec65-109">Ruft ab oder legt den Fehlercode:.</span><span class="sxs-lookup"><span data-stu-id="eec65-109">Gets or sets the error's code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="eec65-110">Ermittelt oder definiert eine menschlichen lesbare Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="eec65-110">Gets or sets a human readable error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eec65-111">Gibt an Ressourcen, die für den Fehler verantwortlich wurden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="eec65-111">Gets or sets indicates resources which were responsible for the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eec65-112">Ruft ab oder legt gibt an, welche Eigenschaft in der Anforderung für den Fehler verantwortlich ist.</span><span class="sxs-lookup"><span data-stu-id="eec65-112">Gets or sets indicates which property in the request is responsible for the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="errorDetail.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eec65-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="eec65-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eec65-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="eec65-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorDetail.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eec65-115">Ruft ab oder legt gibt an, welcher Wert in 'Target' für den Fehler verantwortlich ist.</span><span class="sxs-lookup"><span data-stu-id="eec65-115">Gets or sets indicates which value in 'target' is responsible for the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>