<Type Name="ClientCertificateThumbprint" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint">
  <TypeSignature Language="C#" Value="public class ClientCertificateThumbprint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientCertificateThumbprint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientCertificateThumbprint" />
  <TypeSignature Language="F#" Value="type ClientCertificateThumbprint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a20aa-101">Details der Client-Zertifikat mit Fingerabdruck</span><span class="sxs-lookup"><span data-stu-id="a20aa-101">Client certificate details using thumbprint</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateThumbprint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a20aa-102">Initialisiert eine neue Instanz der ClientCertificateThumbprint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a20aa-102">Initializes a new instance of the ClientCertificateThumbprint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateThumbprint (bool isAdmin, string certificateThumbprint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isAdmin, string certificateThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.#ctor(System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isAdmin As Boolean, certificateThumbprint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint : bool * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint (isAdmin, certificateThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isAdmin" Type="System.Boolean" />
        <Parameter Name="certificateThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isAdmin"><span data-ttu-id="a20aa-103">Dieses Zertifikat für den Administratorzugriff vom Client verwendet wird, wenn "false", sie verwendet wird oder die Abfrage ist nur zugreifen</span><span class="sxs-lookup"><span data-stu-id="a20aa-103">Is this certificate used for admin access from the client, if false, it is used or query only access</span></span></param>
        <param name="certificateThumbprint"><span data-ttu-id="a20aa-104">Certificate thumbprint</span><span class="sxs-lookup"><span data-stu-id="a20aa-104">Certificate thumbprint</span></span></param>
        <summary>
            <span data-ttu-id="a20aa-105">Initialisiert eine neue Instanz der ClientCertificateThumbprint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a20aa-105">Initializes a new instance of the ClientCertificateThumbprint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateThumbprint">
      <MemberSignature Language="C#" Value="public string CertificateThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.CertificateThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertificateThumbprint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.CertificateThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a20aa-106">Ruft ab oder legt ihn fest Fingerabdruck des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="a20aa-106">Gets or sets certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public bool IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : bool with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a20aa-107">Ruft ab oder legt sie fest, wird dieses Zertifikat für den Administratorzugriff vom Client verwendet, wenn "false", er wird verwendet, oder Fragen Sie nur Zugriff auf</span><span class="sxs-lookup"><span data-stu-id="a20aa-107">Gets or sets is this certificate used for admin access from the client, if false, it is used or query only access</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clientCertificateThumbprint.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a20aa-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a20aa-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a20aa-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a20aa-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>