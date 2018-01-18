<Type Name="CustomDomain" FullName="Microsoft.Azure.Management.Storage.Models.CustomDomain">
  <TypeSignature Language="C#" Value="public class CustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDomain extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.CustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDomain" />
  <TypeSignature Language="F#" Value="type CustomDomain = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="113bc-101">Die benutzerdefinierte Domäne dieses Speicherkonto zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="113bc-101">The custom domain assigned to this storage account.</span></span> <span data-ttu-id="113bc-102">Dies kann über das Update festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="113bc-102">This can be set via Update.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CustomDomain.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="113bc-103">Initialisiert eine neue Instanz der CustomDomain-Klasse.</span><span class="sxs-lookup"><span data-stu-id="113bc-103">Initializes a new instance of the CustomDomain class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomain (string name, Nullable&lt;bool&gt; useSubDomain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CustomDomain.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional useSubDomain As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.CustomDomain : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Storage.Models.CustomDomain" Usage="new Microsoft.Azure.Management.Storage.Models.CustomDomain (name, useSubDomain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="113bc-104">Ruft ab oder legt den benutzerdefinierten Domänennamen in das Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="113bc-104">Gets or sets the custom domain name assigned to the storage account.</span></span> <span data-ttu-id="113bc-105">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="113bc-105">Name is the CNAME source.</span></span></param>
        <param name="useSubDomain"><span data-ttu-id="113bc-106">Gibt an, ob die indirekte CName-Überprüfung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="113bc-106">Indicates whether indirect CName validation is enabled.</span></span> <span data-ttu-id="113bc-107">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="113bc-107">Default value is false.</span></span> <span data-ttu-id="113bc-108">Dies sollte nur auf Updates festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="113bc-108">This should only be set on updates.</span></span></param>
        <summary>
            <span data-ttu-id="113bc-109">Initialisiert eine neue Instanz der CustomDomain-Klasse.</span><span class="sxs-lookup"><span data-stu-id="113bc-109">Initializes a new instance of the CustomDomain class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CustomDomain.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.CustomDomain.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="113bc-110">Ruft ab oder legt den benutzerdefinierten Domänennamen in das Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="113bc-110">Gets or sets the custom domain name assigned to the storage account.</span></span> <span data-ttu-id="113bc-111">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="113bc-111">Name is the CNAME source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSubDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseSubDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseSubDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.CustomDomain.UseSubDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSubDomain As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseSubDomain : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.CustomDomain.UseSubDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useSubDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="113bc-112">Gibt an, ob die indirekte CName-Überprüfung aktiviert ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="113bc-112">Gets or sets indicates whether indirect CName validation is enabled.</span></span> <span data-ttu-id="113bc-113">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="113bc-113">Default value is false.</span></span> <span data-ttu-id="113bc-114">Dies sollte nur auf Updates festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="113bc-114">This should only be set on updates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.CustomDomain.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="customDomain.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="113bc-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="113bc-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="113bc-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="113bc-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>