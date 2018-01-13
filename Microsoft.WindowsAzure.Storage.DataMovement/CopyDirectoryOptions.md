<Type Name="CopyDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class CopyDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CopyDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CopyDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type CopyDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Reihe von Optionen, die für den Kopiervorgang-Verzeichnis angegeben werden können
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.BlobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Ziel-Blob. Diese Option wird wirksam, nur beim Kopieren von nicht-Azure-Blob-Speicher in Azure Blob-Speicher. Wenn der Blob-Typ nicht angegeben ist, wird die Datensicherungsdateien verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public char Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance char Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Char" />
      <MemberSignature Language="F#" Value="member this.Delimiter : char with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Char</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Char, der das Trennzeichen zum Trennen der virtuellen Verzeichnisse in einem blobnamen angibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSnapshots">
      <MemberSignature Language="C#" Value="public bool IncludeSnapshots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSnapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.IncludeSnapshots" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSnapshots As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSnapshots : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.CopyDirectoryOptions.IncludeSnapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Flag, der angibt, ob Momentaufnahmen eingeschlossen werden sollen, wenn aus dem Azure-Blob-Speicher kopieren.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn dieses Flag, auf "true" Momentaufnahmen des Quell-Blob festgelegt ist wird als separate Dateien an Ziel kopiert werden. Ein Quell-Blob-Name im Format "x.y" wird angegeben, ist, auf dem "X" ist der Dateiname ohne Erweiterung und den Buchstaben "j" wird die Dateinamenerweiterung der Zieldateiname des Blob-Momentaufnahme als "x (% snapshot_time_stamp%).y" formatiert.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>