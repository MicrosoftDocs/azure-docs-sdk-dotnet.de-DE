<Type Name="ClaimsCredentials" FullName="System.Fabric.ClaimsCredentials">
  <TypeSignature Language="C#" Value="public sealed class ClaimsCredentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClaimsCredentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ClaimsCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClaimsCredentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type ClaimsCredentials = class&#xA;    inherit SecurityCredentials" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.SecurityCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="cbd89-101">Stellt-Anspruchs basierend Sicherheitsanmeldeinformationen aus STS (Sicherheitstokendienst) abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cbd89-101">Represents the claim based security credential acquired from STS (security token service).</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClaimsCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ClaimsCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="cbd89-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ClaimsCredentials" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cbd89-102">Initializes a new instance of the <see cref="T:System.Fabric.ClaimsCredentials" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IssuerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IssuerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.IssuerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IssuerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.IssuerThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cbd89-103">Ruft die zertifikatfingerabdrücke der Server Aussteller des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="cbd89-103">Gets the certificate thumbprints of server certificate issuer.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cbd89-104">Die zertifikatfingerabdrücke der Server Aussteller des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="cbd89-104">The certificate thumbprints of server certificate issuer.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalClaims">
      <MemberSignature Language="C#" Value="public string LocalClaims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalClaims" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.LocalClaims" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalClaims As String" />
      <MemberSignature Language="F#" Value="member this.LocalClaims : string with get, set" Usage="System.Fabric.ClaimsCredentials.LocalClaims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cbd89-105">Ruft eine Zeichenfolgendarstellung von Claims-Token vom STS (Sicherheitstokendienst) bezogen.</span><span class="sxs-lookup"><span data-stu-id="cbd89-105">Gets the string representation of claims token acquired from STS (security token service).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cbd89-106">Die Zeichenfolgendarstellung des Claims-Token vom STS (Sicherheitstokendienst) bezogen werden soll.</span><span class="sxs-lookup"><span data-stu-id="cbd89-106">The string representation of claims token acquired from STS (security token service).</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cbd89-107">Ruft die Schutzebene der Kommunikation mit dem Server ab. Der Standardwert ist <see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />.</span><span class="sxs-lookup"><span data-stu-id="cbd89-107">Gets the protection level of communication with server; the default value is <see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cbd89-108">Die Schutzebene der Kommunikation mit dem Server.</span><span class="sxs-lookup"><span data-stu-id="cbd89-108">The protection level of communication with server.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cbd89-109">Ruft die erwartete allgemeinen Namen des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="cbd89-109">Gets the expected common names of server certificate.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="cbd89-110">Die erwartete allgemeinen Namen des Server-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="cbd89-110">The expected common names of server certificate.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbd89-111">NUR ZUR INTERNEN VERWENDUNG.</span><span class="sxs-lookup"><span data-stu-id="cbd89-111">FOR INTERNAL USE ONLY.</span></span>
            </summary>
        <value><span data-ttu-id="cbd89-112">NUR ZUR INTERNEN VERWENDUNG.</span><span class="sxs-lookup"><span data-stu-id="cbd89-112">FOR INTERNAL USE ONLY.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>