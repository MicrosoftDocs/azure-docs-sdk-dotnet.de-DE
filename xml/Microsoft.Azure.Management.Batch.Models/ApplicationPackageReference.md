<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bbf60-101">Um ein Anwendungspaket in das Batch-Konto verknüpfen</span><span class="sxs-lookup"><span data-stu-id="bbf60-101">Link to an application package inside the batch account</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bbf60-102">Initialisiert eine neue Instanz der ApplicationPackageReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bbf60-102">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference (string id, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference : string * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference" Usage="new Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference (id, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bbf60-103">Die ID des Anwendungspakets zu installieren.</span><span class="sxs-lookup"><span data-stu-id="bbf60-103">The ID of the application package to install.</span></span> <span data-ttu-id="bbf60-104">Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.</span><span class="sxs-lookup"><span data-stu-id="bbf60-104">This must be inside the same batch account as the pool.</span></span> <span data-ttu-id="bbf60-105">Dies kann entweder ein Verweis auf eine bestimmte Version oder die Standardversion sein, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="bbf60-105">This can either be a reference to a specific version or the default version if one exists.</span></span></param>
        <param name="version"><span data-ttu-id="bbf60-106">Die Version der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="bbf60-106">The version of the application to deploy.</span></span> <span data-ttu-id="bbf60-107">Wenn nicht angegeben, wird die Standardversion bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bbf60-107">If omitted, the default version is deployed.</span></span></param>
        <summary>
            <span data-ttu-id="bbf60-108">Initialisiert eine neue Instanz der ApplicationPackageReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bbf60-108">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf60-109">Ruft ab oder legt die ID des Anwendungspakets zu installieren.</span><span class="sxs-lookup"><span data-stu-id="bbf60-109">Gets or sets the ID of the application package to install.</span></span> <span data-ttu-id="bbf60-110">Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.</span><span class="sxs-lookup"><span data-stu-id="bbf60-110">This must be inside the same batch account as the pool.</span></span> <span data-ttu-id="bbf60-111">Dies kann entweder ein Verweis auf eine bestimmte Version oder die Standardversion sein, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="bbf60-111">This can either be a reference to a specific version or the default version if one exists.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationPackageReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bbf60-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bbf60-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bbf60-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bbf60-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf60-114">Ruft ab oder legt die Version der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="bbf60-114">Gets or sets the version of the application to deploy.</span></span> <span data-ttu-id="bbf60-115">Wenn nicht angegeben, wird die Standardversion bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bbf60-115">If omitted, the default version is deployed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bbf60-116">Wenn dies fehlt, und keine Standardversion für diese Anwendung angegeben ist, schlägt die Anforderung mit dem Fehlercode InvalidApplicationPackageReferences fehl.</span><span class="sxs-lookup"><span data-stu-id="bbf60-116">If this is omitted, and no default version is specified for this application, the request fails with the error code InvalidApplicationPackageReferences.</span></span> <span data-ttu-id="bbf60-117">Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 409.</span><span class="sxs-lookup"><span data-stu-id="bbf60-117">If you are calling the REST API directly, the HTTP status code is 409.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>