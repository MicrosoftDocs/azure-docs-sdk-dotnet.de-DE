<Type Name="OutputFile" FullName="Microsoft.Azure.Batch.OutputFile">
  <TypeSignature Language="C#" Value="public class OutputFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFile" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFile" />
  <TypeSignature Language="F#" Value="type OutputFile = class&#xA;    interface ITransportObjectProvider&lt;OutputFile&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Spezifikation für das Hochladen von Dateien aus einem Azure Batch-Knoten an einen anderen Speicherort aus, nachdem der Batch-Dienst beendet wurde, den Task Prozess ausführen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile (string filePattern, Microsoft.Azure.Batch.OutputFileDestination destination, Microsoft.Azure.Batch.OutputFileUploadOptions uploadOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filePattern, class Microsoft.Azure.Batch.OutputFileDestination destination, class Microsoft.Azure.Batch.OutputFileUploadOptions uploadOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFile.#ctor(System.String,Microsoft.Azure.Batch.OutputFileDestination,Microsoft.Azure.Batch.OutputFileUploadOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filePattern As String, destination As OutputFileDestination, uploadOptions As OutputFileUploadOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFile : string * Microsoft.Azure.Batch.OutputFileDestination * Microsoft.Azure.Batch.OutputFileUploadOptions -&gt; Microsoft.Azure.Batch.OutputFile" Usage="new Microsoft.Azure.Batch.OutputFile (filePattern, destination, uploadOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Batch.OutputFileDestination" />
        <Parameter Name="uploadOptions" Type="Microsoft.Azure.Batch.OutputFileUploadOptions" />
      </Parameters>
      <Docs>
        <param name="filePattern">Ein Muster, der angibt, die Ordner hochladen.</param>
        <param name="destination">Das Ziel für die Ausgabedateien.</param>
        <param name="uploadOptions">Zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFile" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OutputFileDestination Destination { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OutputFileDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.Destination" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Destination As OutputFileDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Batch.OutputFileDestination" Usage="Microsoft.Azure.Batch.OutputFile.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OutputFileDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ziel für die Ausgabedateien ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string" Usage="Microsoft.Azure.Batch.OutputFile.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein Muster, der angibt, die Ordner hochladen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Relative und absolute Pfade werden unterstützt. Relative Pfade sind relativ zum Arbeitsverzeichnis Aufgabe. Verwenden Sie Platzhalterzeichen, * auf einem beliebigen Zeichen entspricht und ** mit einem beliebigen Verzeichnis übereinstimmen. Z. B. **\*".txt" entspricht jede Datei in ".txt" in das Arbeitsverzeichnis für den Task oder einem Unterverzeichnis beenden. Beachten Sie, dass \ und / Synonym behandelt und das richtige Verzeichnistrennzeichen unter dem Betriebssystem des Compute-Knoten zugeordnet sind.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OutputFileUploadOptions UploadOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OutputFileUploadOptions UploadOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.UploadOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UploadOptions As OutputFileUploadOptions" />
      <MemberSignature Language="F#" Value="member this.UploadOptions : Microsoft.Azure.Batch.OutputFileUploadOptions" Usage="Microsoft.Azure.Batch.OutputFile.UploadOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OutputFileUploadOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>