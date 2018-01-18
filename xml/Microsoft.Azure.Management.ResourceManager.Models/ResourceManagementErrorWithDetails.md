<Type Name="ResourceManagementErrorWithDetails" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails">
  <TypeSignature Language="C#" Value="public class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceManagementErrorWithDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="F#" Value="type ResourceManagementErrorWithDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d51de-101">Die ausführliche Fehlermeldung der ressourcenverwaltung.</span><span class="sxs-lookup"><span data-stu-id="d51de-101">The detailed error message of resource management.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d51de-102">Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d51de-102">Initializes a new instance of the ResourceManagementErrorWithDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails (string code = null, string message = null, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional target As String = null, Optional details As IList(Of ResourceManagementErrorWithDetails) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="d51de-103">Der Fehlercode zurückgegeben, wenn die Vorlage zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="d51de-103">The error code returned when exporting the template.</span></span></param>
        <param name="message"><span data-ttu-id="d51de-104">Die Fehlermeldung, die Beschreibung des Fehlers exportieren.</span><span class="sxs-lookup"><span data-stu-id="d51de-104">The error message describing the export error.</span></span></param>
        <param name="target"><span data-ttu-id="d51de-105">Das Ziel des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="d51de-105">The target of the error.</span></span></param>
        <param name="details"><span data-ttu-id="d51de-106">Validierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="d51de-106">Validation error.</span></span></param>
        <summary>
            <span data-ttu-id="d51de-107">Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d51de-107">Initializes a new instance of the ResourceManagementErrorWithDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="d51de-108">Ruft den beim Exportieren der Vorlage zurückgegebenen Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="d51de-108">Gets the error code returned when exporting the template.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As IList(Of ResourceManagementErrorWithDetails)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d51de-109">Ruft die Validierungsfehler ab.</span><span class="sxs-lookup"><span data-stu-id="d51de-109">Gets validation error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="d51de-110">Ruft die Beschreibung des Fehlers Export Fehlermeldung ab.</span><span class="sxs-lookup"><span data-stu-id="d51de-110">Gets the error message describing the export error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d51de-111">Ruft das Ziel des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="d51de-111">Gets the target of the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>