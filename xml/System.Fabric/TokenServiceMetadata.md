<Type Name="TokenServiceMetadata" FullName="System.Fabric.TokenServiceMetadata">
  <TypeSignature Language="C#" Value="public sealed class TokenServiceMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit TokenServiceMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TokenServiceMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenServiceMetadata" />
  <TypeSignature Language="F#" Value="type TokenServiceMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="6a600-101">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="6a600-101">For internal use only.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenServiceMetadata (string metadata, string serviceName, string serviceDnsName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadata, string serviceName, string serviceDnsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TokenServiceMetadata.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metadata As String, serviceName As String, serviceDnsName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TokenServiceMetadata : string * string * string -&gt; System.Fabric.TokenServiceMetadata" Usage="new System.Fabric.TokenServiceMetadata (metadata, serviceName, serviceDnsName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadata" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="serviceDnsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="metadata">
          <para><span data-ttu-id="6a600-102">Die Metadaten.</span><span class="sxs-lookup"><span data-stu-id="6a600-102">The metadata.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="6a600-103">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6a600-103">The service name.</span></span></para>
        </param>
        <param name="serviceDnsName">
          <para><span data-ttu-id="6a600-104">Der Dienst-DNS-Name.</span><span class="sxs-lookup"><span data-stu-id="6a600-104">The service Dns name.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="6a600-105">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="6a600-105">For internal use only.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public string Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Metadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TokenServiceMetadata.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As String" />
      <MemberSignature Language="F#" Value="member this.Metadata : string with get, set" Usage="System.Fabric.TokenServiceMetadata.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="6a600-106">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="6a600-106">For internal use only.</span></span>
            <span data-ttu-id="6a600-107">Ruft ab oder legt die Metadaten.</span><span class="sxs-lookup"><span data-stu-id="6a600-107">Gets or sets the metadata.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="6a600-108">Die Metadaten.</span><span class="sxs-lookup"><span data-stu-id="6a600-108">The metadata.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TokenServiceMetadata.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string with get, set" Usage="System.Fabric.TokenServiceMetadata.ServiceDnsName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ServiceDnsName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="6a600-109">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="6a600-109">For internal use only.</span></span>
            <span data-ttu-id="6a600-110">Ruft ab oder legt die DNS-Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6a600-110">Gets or sets the service Dns name.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="6a600-111">Der Dienst-DNS-Name.</span><span class="sxs-lookup"><span data-stu-id="6a600-111">The service Dns name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TokenServiceMetadata.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string with get, set" Usage="System.Fabric.TokenServiceMetadata.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="6a600-112">Nur zur internen Verwendung.</span><span class="sxs-lookup"><span data-stu-id="6a600-112">For internal use only.</span></span>
            <span data-ttu-id="6a600-113">Ruft ab oder legt den Dienstnamen.</span><span class="sxs-lookup"><span data-stu-id="6a600-113">Gets or sets the service name.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="6a600-114">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="6a600-114">The service name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>