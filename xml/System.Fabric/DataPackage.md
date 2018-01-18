<Type Name="DataPackage" FullName="System.Fabric.DataPackage">
  <TypeSignature Language="C#" Value="public sealed class DataPackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataPackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataPackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataPackage" />
  <TypeSignature Language="F#" Value="type DataPackage = class" />
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
      <para><span data-ttu-id="e5089-101">Diese Klasse stellt ein Datenpaket in der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="e5089-101">This class represents a data package in the application.</span></span> <span data-ttu-id="e5089-102">Ein Datenpaket besteht aus statischen Daten (die ein Upgrade ausgeführt werden können), die von der Anwendung verarbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="e5089-102">A data package consists of static data (that can be upgraded) that is consumed by the application.</span></span> <span data-ttu-id="e5089-103">Weitere Informationen finden Sie unter https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span><span class="sxs-lookup"><span data-stu-id="e5089-103">For more information see https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.DataPackageDescription Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.Description : System.Fabric.Description.DataPackageDescription" Usage="System.Fabric.DataPackage.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e5089-104">Ruft die <see cref="T:System.Fabric.Description.PackageDescription" /> zugeordnete Objekt der <see cref="T:System.Fabric.DataPackage" />.</span><span class="sxs-lookup"><span data-stu-id="e5089-104">Gets the <see cref="T:System.Fabric.Description.PackageDescription" /> object associated with the <see cref="T:System.Fabric.DataPackage" />.</span></span> <span data-ttu-id="e5089-105">Die paketbeschreibung kann verwendet werden, Zugriff auf zusätzliche Informationen über dieses Paket wie den Namen, Version usw.</span><span class="sxs-lookup"><span data-stu-id="e5089-105">The package description can be used to access additional information about this package such as the name, version etc.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="e5089-106">Das <see cref="T:System.Fabric.Description.PackageDescription" /> zugeordnete <see cref="T:System.Fabric.DataPackage" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="e5089-106">The <see cref="T:System.Fabric.Description.PackageDescription" /> object associated with the <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.DataPackage.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="System.Fabric.DataPackage.Path" />
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
          <para><span data-ttu-id="e5089-107">Ruft den lokalen Pfad der <see cref="T:System.Fabric.DataPackage" />.</span><span class="sxs-lookup"><span data-stu-id="e5089-107">Gets the local path of <see cref="T:System.Fabric.DataPackage" />.</span></span> <span data-ttu-id="e5089-108">Dieser Pfad enthält den Inhalt des Datenpakets.</span><span class="sxs-lookup"><span data-stu-id="e5089-108">This path contains the contents of the data package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e5089-109">Der lokale Pfad der <see cref="T:System.Fabric.DataPackage" />.</span><span class="sxs-lookup"><span data-stu-id="e5089-109">The local path of <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>