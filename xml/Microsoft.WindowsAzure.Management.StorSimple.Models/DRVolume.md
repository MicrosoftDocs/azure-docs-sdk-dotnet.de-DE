<Type Name="DRVolume" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume">
  <TypeSignature Language="C#" Value="public class DRVolume" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DRVolume extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume" />
  <TypeSignature Language="VB.NET" Value="Public Class DRVolume" />
  <TypeSignature Language="F#" Value="type DRVolume = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9242c-101">Stellt ein Volume als in einen Sicherungssnapshot vorhanden</span><span class="sxs-lookup"><span data-stu-id="9242c-101">Represents a volume as present in a backup snapshot</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DRVolume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9242c-102">Initialisiert eine neue Instanz der DRVolume-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9242c-102">Initializes a new instance of the DRVolume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DRVolume (string displayName, long size, string snapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string displayName, int64 size, string snapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.#ctor(System.String,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (displayName As String, size As Long, snapshotId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume : string * int64 * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume (displayName, size, snapshotId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="size" Type="System.Int64" />
        <Parameter Name="snapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName">To be added.</param>
        <param name="size">To be added.</param>
        <param name="snapshotId">To be added.</param>
        <summary>
            <span data-ttu-id="9242c-103">Initialisiert eine neue Instanz der DRVolume-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="9242c-103">Initializes a new instance of the DRVolume class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9242c-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9242c-104">Required.</span></span> <span data-ttu-id="9242c-105">Der Anzeigename</span><span class="sxs-lookup"><span data-stu-id="9242c-105">The display name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.Size" />
      <MemberSignature Language="VB.NET" Value="Public Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9242c-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9242c-106">Required.</span></span> <span data-ttu-id="9242c-107">Größe der Momentaufnahme</span><span class="sxs-lookup"><span data-stu-id="9242c-107">Size of the snapshot</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotId">
      <MemberSignature Language="C#" Value="public string SnapshotId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SnapshotId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.SnapshotId" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotId As String" />
      <MemberSignature Language="F#" Value="member this.SnapshotId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DRVolume.SnapshotId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9242c-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9242c-108">Required.</span></span> <span data-ttu-id="9242c-109">Der momentaufnahmebezeichner</span><span class="sxs-lookup"><span data-stu-id="9242c-109">The snapshot identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>