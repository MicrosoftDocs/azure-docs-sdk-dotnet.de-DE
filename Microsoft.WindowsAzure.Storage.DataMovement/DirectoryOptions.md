<Type Name="DirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions">
  <TypeSignature Language="C#" Value="public class DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DirectoryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DirectoryOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Reihe von Optionen, die für den Übertragungsvorgang Verzeichnis angegeben werden können
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.#ctor" />
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
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public bool Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.Recursive : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
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
            Ruft ab, oder einen booleschen Wert ab, der angibt, ob Unterverzeichnisse enthalten, bei einem Übertragungsvorgang Verzeichnis.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchPattern">
      <MemberSignature Language="C#" Value="public string SearchPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchPattern As String" />
      <MemberSignature Language="F#" Value="member this.SearchPattern : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Zeichenfolge, die verwendet wird, um die Überprüfung der Namen von Dateien auf Übereinstimmungen.
            </summary>
        <value>To be added.</value>
        <remarks>
            SearchPattern Übereinstimmung unterscheidet sich für verschiedene Datenquellentypen zu Verzeichnis und die Einstellung der rekursiven: bei der Quelle lokalen Verzeichnispfad ist, wird mit Quelldateinamen als Standardplatzhalter SearchPattern abgeglichen. Wenn Recuresive auf "false" festgelegt ist, werden nur die Dateien direkt unterhalb des Quellverzeichnisses zugeordnet werden. Andernfalls werden alle Dateien in das Unterverzeichnis ebenfalls zugeordnet.
            
            Wenn Quelle Azure Blob-Verzeichnis ist, wenn Recuresive auf "true", "SearchPattern festgelegt ist wird als Präfix für Quell-Blob verglichen.
            Andernfalls, nur Azure-Blob mit dem genauen Namen SearchPattern gemäß wird abgeglichen werden.
            
            Wenn Quelle Azure Dateiverzeichnis, ist, wenn rekursive auf "true", "SearchPattern festgelegt ist, wird nicht unterstützt. Andernfalls werden nur Azure-Datei mit dem genauen Namen gemäß SearchPattern zugeordnet werden.
            
            Wenn SearchPattern nicht angegeben ist, "*.*" für lokales Verzeichnis Quelle beim leere Zeichenfolge für Azure Blob-Datei-Verzeichnis verwendet werden. So geben Sie das Suchmuster entweder oder rekursiv auf bei "true" festgelegt Quelle Directory Azure Blob-Datei ist, andernfalls keine Blob-Datei abgeglichen werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>