<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.Protocol.Models.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class" />
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
            Eine Datei, die auf einem Serverknoten aus dem Azure-Blob-Speicher heruntergeladen werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse ResourceFile an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ResourceFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile (blobSource, filePath, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobSource" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobSource">Die URL der Datei innerhalb des Azure-Blob-Speicher.</param>
        <param name="filePath">Der Speicherort auf den Serverknoten, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task.</param>
        <param name="fileMode">Die Datei Berechtigung Mode-Attribut im Oktalformat.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse ResourceFile an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL der Datei innerhalb des Azure-Blob-Speicher.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese URL muss anonyme Zugriff verwendet werden können; der Batch-Dienst darstellen, also keine Anmeldeinformationen, beim Herunterladen von BLOBs. Es gibt zwei Möglichkeiten, einen solchen URL für ein Blob im Azure-Speicher: eine Shared Access Signature (SAS) ein, Gewähren von Lese-und Schreibberechtigungen für das Blob enthalten, oder legen Sie die Zugriffssteuerungsliste für das Blob oder den Container öffentlichen Zugriff zulassen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Datei Berechtigung Mode-Attribut im Oktalformat.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft gilt nur für Dateien, die für Linux-Serverknoten heruntergeladen werden. Es wird ignoriert, wenn sie für eine ResourceFile angegeben ist, die auf einem Windows-Knoten heruntergeladen werden. Wenn diese Eigenschaft nicht für einen Linux-Knoten angegeben wird, wird ein Standardwert von 0770 in die Datei angewendet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicherort auf den Serverknoten, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceFile.Validate " />
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