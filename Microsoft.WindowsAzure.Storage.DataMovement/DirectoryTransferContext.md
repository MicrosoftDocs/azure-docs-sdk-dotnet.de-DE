<Type Name="DirectoryTransferContext" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext">
  <TypeSignature Language="C#" Value="public class DirectoryTransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DirectoryTransferContext extends Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryTransferContext&#xA;Inherits TransferContext" />
  <TypeSignature Language="F#" Value="type DirectoryTransferContext = class&#xA;    inherit TransferContext" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.TransferContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23ffc-101">Stellt den Kontext für eine Übertragung Verzeichnis dar und bietet zusätzliche Laufzeitinformationen zu dessen Ausführung.</span><span class="sxs-lookup"><span data-stu-id="23ffc-101">Represents the context for a directory transfer, and provides additional runtime information about its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryTransferContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23ffc-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23ffc-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryTransferContext (Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (checkpoint As TransferCheckpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint -&gt; Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext checkpoint" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint"><span data-ttu-id="23ffc-103">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" /> Objekt, das den letzten Prüfpunkt aus der die Übertragung fortgesetzt wird darstellt.</span><span class="sxs-lookup"><span data-stu-id="23ffc-103">An <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" /> object representing the last checkpoint from which the transfer continues on.</span></span></param>
        <summary>
            <span data-ttu-id="23ffc-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23ffc-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryTransferContext (System.IO.Stream journalStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream journalStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (journalStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext journalStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="journalStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="journalStream"><span data-ttu-id="23ffc-105">Der Stream, in dem die Übertragung Journal Infos in geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="23ffc-105">The stream into which the transfer journal info will be written into.</span></span> <span data-ttu-id="23ffc-106">Sie können die Previours fortsetzen Übertragung von seinen Stream Journal angehalten.</span><span class="sxs-lookup"><span data-stu-id="23ffc-106">It can resume the previours paused transfer from its journal stream.</span></span></param>
        <summary>
            <span data-ttu-id="23ffc-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23ffc-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldTransferCallback">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback ShouldTransferCallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback ShouldTransferCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext.ShouldTransferCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldTransferCallback As ShouldTransferCallback" />
      <MemberSignature Language="F#" Value="member this.ShouldTransferCallback : Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryTransferContext.ShouldTransferCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23ffc-108">Ruft ab oder legt den Rückruf aufgerufen wird, um festzustellen, ob eine Übertragung erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="23ffc-108">Gets or sets the callback invoked to tell whether a transfer should be done.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>