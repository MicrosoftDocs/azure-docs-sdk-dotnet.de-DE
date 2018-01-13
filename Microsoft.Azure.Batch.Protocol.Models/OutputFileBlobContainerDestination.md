<Type Name="OutputFileBlobContainerDestination" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination">
  <TypeSignature Language="C#" Value="public class OutputFileBlobContainerDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileBlobContainerDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileBlobContainerDestination" />
  <TypeSignature Language="F#" Value="type OutputFileBlobContainerDestination = class" />
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
            Gibt eine Datei hochladen Ziel innerhalb einer Azure-Blob-Speichercontainer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der OutputFileBlobContainerDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination (string containerUrl, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerUrl, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerUrl As String, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination (containerUrl, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerUrl" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerUrl">Die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</param>
        <param name="path">Der Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container.</param>
        <summary>
            Initialisiert eine neue Instanz der OutputFileBlobContainerDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerUrl">
      <MemberSignature Language="C#" Value="public string ContainerUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ContainerUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die URL muss eine Shared Access Signature (SAS) ein, erteilen Schreibberechtigungen für den Container enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, die Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn FilePattern auf eine bestimmte Datei verweist (d. h. keine Platzhalter enthält), dann lautet der Name des Blob, an dem diese Datei hochladen. Wenn FilePattern mindestens ein Platzhalterzeichen enthält (und daher möglicherweise mehrere Dateien übereinstimmen), ist Pfad den Namen des virtuellen Blob-Verzeichnisses (die einzelnen blobnamen vorangestellt ist), um Dateien hochzuladen. Wenn nicht angegeben, werden die Dateien in das Stammverzeichnis des Containers mit einem übereinstimmenden Dateinamen blobnamen hochgeladen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFileBlobContainerDestination.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>