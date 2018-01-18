<Type Name="CertificateCreateHeaders" FullName="Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders">
  <TypeSignature Language="C#" Value="public class CertificateCreateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCreateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCreateHeaders" />
  <TypeSignature Language="F#" Value="type CertificateCreateHeaders = class" />
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
            <span data-ttu-id="c87e5-101">Definiert die Header für den Erstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="c87e5-101">Defines headers for Create operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c87e5-102">Initialisiert eine neue Instanz der CertificateCreateHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c87e5-102">Initializes a new instance of the CertificateCreateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders : string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="c87e5-103">Der ETag-HTTP-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="c87e5-103">The ETag HTTP response header.</span></span> <span data-ttu-id="c87e5-104">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c87e5-104">This is an opaque string.</span></span> <span data-ttu-id="c87e5-105">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="c87e5-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="c87e5-106">Insbesondere können Sie das ETag an einem der If-Match- oder If-None-Match-Header übergeben.</span><span class="sxs-lookup"><span data-stu-id="c87e5-106">In particular, you can pass the ETag to one of the If-Match or If-None-Match headers.</span></span></param>
        <summary>
            <span data-ttu-id="c87e5-107">Initialisiert eine neue Instanz der CertificateCreateHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c87e5-107">Initializes a new instance of the CertificateCreateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c87e5-108">Ruft ab oder legt den ETag-HTTP-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="c87e5-108">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="c87e5-109">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c87e5-109">This is an opaque string.</span></span> <span data-ttu-id="c87e5-110">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="c87e5-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="c87e5-111">Insbesondere können Sie das ETag an einem der If-Match- oder If-None-Match-Header übergeben.</span><span class="sxs-lookup"><span data-stu-id="c87e5-111">In particular, you can pass the ETag to one of the If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>