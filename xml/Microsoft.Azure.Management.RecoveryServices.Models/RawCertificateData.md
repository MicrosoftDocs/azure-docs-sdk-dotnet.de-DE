<Type Name="RawCertificateData" FullName="Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData">
  <TypeSignature Language="C#" Value="public class RawCertificateData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RawCertificateData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData" />
  <TypeSignature Language="VB.NET" Value="Public Class RawCertificateData" />
  <TypeSignature Language="F#" Value="type RawCertificateData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5fd08-101">Die Rohzertifikatdaten.</span><span class="sxs-lookup"><span data-stu-id="5fd08-101">Raw certificate data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RawCertificateData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5fd08-102">Initialisiert eine neue Instanz der RawCertificateData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fd08-102">Initializes a new instance of the RawCertificateData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RawCertificateData (string authType = null, byte[] certificate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authType, unsigned int8[] certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional authType As String = null, Optional certificate As Byte() = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData : string * byte[] -&gt; Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData (authType, certificate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authType" Type="System.String" />
        <Parameter Name="certificate" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="authType"><span data-ttu-id="5fd08-103">Gibt den Authentifizierungstyp an.</span><span class="sxs-lookup"><span data-stu-id="5fd08-103">Specifies the authentication type.</span></span> <span data-ttu-id="5fd08-104">Folgende Werte sind möglich: "Ungültig", "ACS", "AAD", "AccessControlService", "AzureActiveDirectory"</span><span class="sxs-lookup"><span data-stu-id="5fd08-104">Possible values include: 'Invalid', 'ACS', 'AAD', 'AccessControlService', 'AzureActiveDirectory'</span></span></param>
        <param name="certificate"><span data-ttu-id="5fd08-105">Die base64-codierte Zertifikat Rohdaten Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5fd08-105">The base64 encoded certificate raw data string</span></span></param>
        <summary>
            <span data-ttu-id="5fd08-106">Initialisiert eine neue Instanz der RawCertificateData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5fd08-106">Initializes a new instance of the RawCertificateData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthType">
      <MemberSignature Language="C#" Value="public string AuthType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.AuthType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthType As String" />
      <MemberSignature Language="F#" Value="member this.AuthType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.AuthType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fd08-107">Ruft ab oder legt gibt den Authentifizierungstyp an.</span><span class="sxs-lookup"><span data-stu-id="5fd08-107">Gets or sets specifies the authentication type.</span></span> <span data-ttu-id="5fd08-108">Folgende Werte sind möglich: "Ungültig", "ACS", "AAD", "AccessControlService", "AzureActiveDirectory"</span><span class="sxs-lookup"><span data-stu-id="5fd08-108">Possible values include: 'Invalid', 'ACS', 'AAD', 'AccessControlService', 'AzureActiveDirectory'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public byte[] Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As Byte()" />
      <MemberSignature Language="F#" Value="member this.Certificate : byte[] with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.RawCertificateData.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fd08-109">Ruft ab oder legt die base64-codierte Zertifikat Rohdaten-Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="5fd08-109">Gets or sets the base64 encoded certificate raw data string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>