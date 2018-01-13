<Type Name="ResourceManagementErrorWithDetails" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails">
  <TypeSignature Language="C#" Value="public class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceManagementErrorWithDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="F#" Value="type ResourceManagementErrorWithDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e5c3-101">Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-101">Initializes a new instance of the ResourceManagementErrorWithDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails (string code, string message, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional target As String = null, Optional details As IList(Of ResourceManagementErrorWithDetails) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="3e5c3-102">Der Fehlercode, der vom Server zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-102">The error code returned from the server.</span></span></param>
        <param name="message"><span data-ttu-id="3e5c3-103">Die Fehlermeldung, die vom Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-103">The error message returned from the server.</span></span></param>
        <param name="target"><span data-ttu-id="3e5c3-104">Das Ziel des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-104">The target of the error.</span></span></param>
        <param name="details"><span data-ttu-id="3e5c3-105">Validierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-105">Validation error.</span></span></param>
        <summary>
            <span data-ttu-id="3e5c3-106">Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-106">Initializes a new instance of the ResourceManagementErrorWithDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e5c3-107">Ruft ab oder legt den vom Server zurückgegebenen Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-107">Gets or sets the error code returned from the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of ResourceManagementErrorWithDetails)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e5c3-108">Ruft ab, oder legt ihn fest Validierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-108">Gets or sets validation error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e5c3-109">Ruft ab oder legt die vom Server zurückgegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-109">Gets or sets the error message returned from the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3e5c3-110">Ruft ab oder legt das Ziel des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-110">Gets or sets the target of the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceManagementErrorWithDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceManagementErrorWithDetails.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e5c3-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3e5c3-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3e5c3-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3e5c3-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>