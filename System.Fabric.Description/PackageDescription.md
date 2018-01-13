<Type Name="PackageDescription" FullName="System.Fabric.Description.PackageDescription">
  <TypeSignature Language="C#" Value="public abstract class PackageDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PackageDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PackageDescription" />
  <TypeSignature Language="F#" Value="type PackageDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="38727-101">Stellt eine Basisklasse für alle Paket Beschreibungen dar.</span><span class="sxs-lookup"><span data-stu-id="38727-101">Represents a base class for all package descriptions.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PackageDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.PackageDescription.Name" />
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
          <para><span data-ttu-id="38727-102">Ruft den Namen des Pakets ab.</span><span class="sxs-lookup"><span data-stu-id="38727-102">Gets the name of the package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="38727-103">Der Name des Pakets.</span><span class="sxs-lookup"><span data-stu-id="38727-103">The name of the package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PackageDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.Description.PackageDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use Path property in System.Fabric.CodePackage, System.Fabric.ConfigurationPackage or System.Fabric.DataPackage types.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="38727-104">Ruft den Pfad des Pakets ab.</span><span class="sxs-lookup"><span data-stu-id="38727-104">Gets the path to the package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="38727-105">Der Pfad zum Paket.</span><span class="sxs-lookup"><span data-stu-id="38727-105">The path to the package.</span></span></para>
        </value>
        <remarks><span data-ttu-id="38727-106">Diese Eigenschaft ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="38727-106">This property is obsolete.</span></span>
            <span data-ttu-id="38727-107">Verwenden Sie die Path-Eigenschaft in <see cref="T:System.Fabric.CodePackage" />, <see cref="T:System.Fabric.ConfigurationPackage" /> oder <see cref="T:System.Fabric.DataPackage" /> Typen.</span><span class="sxs-lookup"><span data-stu-id="38727-107">Use Path property in <see cref="T:System.Fabric.CodePackage" />, <see cref="T:System.Fabric.ConfigurationPackage" /> or <see cref="T:System.Fabric.DataPackage" /> types.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PackageDescription.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Description.PackageDescription.ServiceManifestName" />
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
          <para><span data-ttu-id="38727-108">Ruft den Namen des Manifests Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="38727-108">Gets the name of the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="38727-109">Der Name des im Dienstmanifest.</span><span class="sxs-lookup"><span data-stu-id="38727-109">The name of the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PackageDescription.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Description.PackageDescription.ServiceManifestVersion" />
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
          <para><span data-ttu-id="38727-110">Ruft die dienstmanifestversion ab.</span><span class="sxs-lookup"><span data-stu-id="38727-110">Gets the service manifest version.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="38727-111">Die dienstmanifestversion.</span><span class="sxs-lookup"><span data-stu-id="38727-111">The service manifest version.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PackageDescription.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="System.Fabric.Description.PackageDescription.Version" />
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
          <para><span data-ttu-id="38727-112">Ruft die Version des Pakets ab.</span><span class="sxs-lookup"><span data-stu-id="38727-112">Gets the version of the package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="38727-113">Die Version des Pakets.</span><span class="sxs-lookup"><span data-stu-id="38727-113">The version of the package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>