<Type Name="HostIsolationMode" FullName="System.Fabric.HostIsolationMode">
  <TypeSignature Language="C#" Value="public enum HostIsolationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed HostIsolationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.HostIsolationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum HostIsolationMode" />
  <TypeSignature Language="F#" Value="type HostIsolationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Gibt an, wird der Isolationsmodus des Haupteinstiegspunkt eines Pakets Code bei Hosttyp <see cref="F:System.Fabric.HostType.ContainerHost" />. <span data-ttu-id="e0a10-102">Dies wird im Rahmen der Container-Host-Richtlinien im Anwendungsmanifest angegeben, beim Dienstmanifest importieren.</span><span class="sxs-lookup"><span data-stu-id="e0a10-102">This is specified as part of container host policies in application manifest while importing service manifest.</span></span>
            </para>
      <remarks>
            <span data-ttu-id="e0a10-103">Geben Sie für Host außer <see cref="F:System.Fabric.HostType.ContainerHost" />, ihr Wert ist <see cref="F:System.Fabric.HostIsolationMode.None" />.</span><span class="sxs-lookup"><span data-stu-id="e0a10-103">For host type other than <see cref="F:System.Fabric.HostType.ContainerHost" />, its value is <see cref="F:System.Fabric.HostIsolationMode.None" />.</span></span>
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HyperV">
      <MemberSignature Language="C#" Value="HyperV" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode HyperV = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.HyperV" />
      <MemberSignature Language="VB.NET" Value="HyperV" />
      <MemberSignature Language="F#" Value="HyperV = 2" Usage="System.Fabric.HostIsolationMode.HyperV" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="e0a10-104">Gibt an, die <see cref="F:System.Fabric.HostType.ContainerHost" /> ist ein Hyper-V-Container.</span><span class="sxs-lookup"><span data-stu-id="e0a10-104">Indicates the <see cref="F:System.Fabric.HostType.ContainerHost" /> is a Hyper-V container.</span></span>
            <span data-ttu-id="e0a10-105">Dies gilt für nur Windows-Containern.</span><span class="sxs-lookup"><span data-stu-id="e0a10-105">This applies to only Windows containers.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.HostIsolationMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e0a10-106">Gibt an, Isolationsmodus gilt nicht für den angegebenen <see cref="T:System.Fabric.HostType" />.</span><span class="sxs-lookup"><span data-stu-id="e0a10-106">Indicates isolation mode is not applicable for given <see cref="T:System.Fabric.HostType" />.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="Process" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode Process = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.Process" />
      <MemberSignature Language="VB.NET" Value="Process" />
      <MemberSignature Language="F#" Value="Process = 1" Usage="System.Fabric.HostIsolationMode.Process" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e0a10-107">Der Standardmodus für die Isolation für eine <see cref="F:System.Fabric.HostType.ContainerHost" />.</span><span class="sxs-lookup"><span data-stu-id="e0a10-107">The default isolation mode for a <see cref="F:System.Fabric.HostType.ContainerHost" />.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>