<Type Name="WinRMListener" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener">
  <TypeSignature Language="C#" Value="public class WinRMListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WinRMListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WinRMListener" />
  <TypeSignature Language="F#" Value="type WinRMListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6dabb-101">Beschreibt, Protokoll und den Fingerabdruck des Listeners für Windows-Remoteverwaltung</span><span class="sxs-lookup"><span data-stu-id="6dabb-101">Describes Protocol and thumbprint of Windows Remote Management listener</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6dabb-102">Initialisiert eine neue Instanz der WinRMListener-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6dabb-102">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener (Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; protocol = null, string certificateUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; protocol, string certificateUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As Nullable(Of ProtocolTypes) = null, Optional certificateUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener (protocol, certificateUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt;" />
        <Parameter Name="certificateUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="6dabb-103">Das von der WinRM-Listener verwendete Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6dabb-103">The Protocol used by the WinRM listener.</span></span>
            <span data-ttu-id="6dabb-104">HTTP- und Https werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6dabb-104">Http and Https are supported.</span></span> <span data-ttu-id="6dabb-105">Folgende Werte sind möglich: "Http", "Https"</span><span class="sxs-lookup"><span data-stu-id="6dabb-105">Possible values include: 'Http', 'Https'</span></span></param>
        <param name="certificateUrl"><span data-ttu-id="6dabb-106">Die Zertifikat-URL in KMS für Https-Listener.</span><span class="sxs-lookup"><span data-stu-id="6dabb-106">The Certificate URL in KMS for Https listeners.</span></span> <span data-ttu-id="6dabb-107">Sollte für HTTP-Listener null sein.</span><span class="sxs-lookup"><span data-stu-id="6dabb-107">Should be null for Http listeners.</span></span></param>
        <summary>
            <span data-ttu-id="6dabb-108">Initialisiert eine neue Instanz der WinRMListener-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6dabb-108">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6dabb-109">Ruft ab oder legt die Zertifikat-URL in KMS für Https-Listener.</span><span class="sxs-lookup"><span data-stu-id="6dabb-109">Gets or sets the Certificate URL in KMS for Https listeners.</span></span> <span data-ttu-id="6dabb-110">Sollte für HTTP-Listener null sein.</span><span class="sxs-lookup"><span data-stu-id="6dabb-110">Should be null for Http listeners.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As Nullable(Of ProtocolTypes)" />
      <MemberSignature Language="F#" Value="member this.Protocol : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6dabb-111">Ruft ab oder legt das von der WinRM-Listener verwendete Protokoll.</span><span class="sxs-lookup"><span data-stu-id="6dabb-111">Gets or sets the Protocol used by the WinRM listener.</span></span> <span data-ttu-id="6dabb-112">HTTP- und Https werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6dabb-112">Http and Https are supported.</span></span> <span data-ttu-id="6dabb-113">Folgende Werte sind möglich: "Http", "Https"</span><span class="sxs-lookup"><span data-stu-id="6dabb-113">Possible values include: 'Http', 'Https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>