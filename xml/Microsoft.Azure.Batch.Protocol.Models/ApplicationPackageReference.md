<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b76dd-101">Ein Verweis auf ein Anwendungspaket erstellen, die bereitgestellt werden, um den Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="b76dd-101">A reference to an application package to be deployed to compute nodes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b76dd-102">Initialisiert eine neue Instanz der ApplicationPackageReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b76dd-102">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference (string applicationId, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string applicationId, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationId As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference (applicationId, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="b76dd-103">Die ID der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="b76dd-103">The ID of the application to deploy.</span></span></param>
        <param name="version"><span data-ttu-id="b76dd-104">Die Version der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="b76dd-104">The version of the application to deploy.</span></span> <span data-ttu-id="b76dd-105">Wenn nicht angegeben, wird die Standardversion bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="b76dd-105">If omitted, the default version is deployed.</span></span></param>
        <summary>
            <span data-ttu-id="b76dd-106">Initialisiert eine neue Instanz der ApplicationPackageReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b76dd-106">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public string ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b76dd-107">Ruft ab oder legt die ID der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="b76dd-107">Gets or sets the ID of the application to deploy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationPackageReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b76dd-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b76dd-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b76dd-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b76dd-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="b76dd-110">Ruft ab oder legt die Version der Anwendung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="b76dd-110">Gets or sets the version of the application to deploy.</span></span> <span data-ttu-id="b76dd-111">Wenn nicht angegeben, wird die Standardversion bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="b76dd-111">If omitted, the default version is deployed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b76dd-112">Wenn diese für einen Pool ausgelassen wird und keine Standardversion für diese Anwendung angegeben wird, schlägt die Anforderung mit dem Fehlercode InvalidApplicationPackageReferences und HTTP-Statuscode 409 fehl.</span><span class="sxs-lookup"><span data-stu-id="b76dd-112">If this is omitted on a pool, and no default version is specified for this application, the request fails with the error code InvalidApplicationPackageReferences and HTTP status code 409.</span></span> <span data-ttu-id="b76dd-113">Wenn weggelassen, auf eine Aufgabe wird, und keine Standardversion für diese Anwendung angegeben ist, scheitert die Aufgabe mit einem vorab verarbeiteten Fehler.</span><span class="sxs-lookup"><span data-stu-id="b76dd-113">If this is omitted on a task, and no default version is specified for this application, the task fails with a pre-processing error.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>