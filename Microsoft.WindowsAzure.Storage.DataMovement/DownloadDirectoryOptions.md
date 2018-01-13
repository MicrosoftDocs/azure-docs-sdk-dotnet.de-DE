<Type Name="DownloadDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class DownloadDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DownloadDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DownloadDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DownloadDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
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
            Stellt eine Reihe von Optionen, die für Download Verzeichnisoperation angegeben werden können
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.#ctor" />
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
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public char Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance char Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Char" />
      <MemberSignature Language="F#" Value="member this.Delimiter : char with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
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
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public bool DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
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
            Ruft ab oder legt ein Flag, das angibt, ob die Content-MD5 oder beim Lesen nicht von Daten aus dem Quellobjekt zu überprüfen.
            Wenn es sich bei festlegen auf "true", "Quellobjekt Content MD5 überprüft wird; Andernfalls wird Quellinhalt MD5-Objekt nicht überprüft werden.
            Wenn nicht angegeben ist, wird standardmäßig auf "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSnapshots">
      <MemberSignature Language="C#" Value="public bool IncludeSnapshots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSnapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSnapshots As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSnapshots : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
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
            Ruft ab oder legt ein Flag, der angibt, ob Momentaufnahmen eingeschlossen werden sollen, beim Herunterladen von Azure Blob-Speicher.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn dieses Flag, auf "true" Momentaufnahmen des Quell-Blob festgelegt ist wird als separate Dateien an Ziel kopiert werden. Ein Quell-Blob-Name im Format "x.y" wird angegeben, ist, auf dem "X" ist der Dateiname ohne Erweiterung und den Buchstaben "j" wird die Dateinamenerweiterung der Zieldateiname des Blob-Momentaufnahme als "x (% snapshot_time_stamp%).y" formatiert.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>