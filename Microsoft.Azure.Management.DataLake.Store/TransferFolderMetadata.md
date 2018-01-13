<Type Name="TransferFolderMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata">
  <TypeSignature Language="C#" Value="public class TransferFolderMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderMetadata" />
  <TypeSignature Language="F#" Value="type TransferFolderMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("FileCount = {FileCount}, TransferId = {TransferId}, IsRecursive = {IsRecursive}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Allgemeine Metadaten, die für eine Übertragung darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferFolderMetadata (string metadataFilePath, Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataFilePath, class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata : string * Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter -&gt; Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata (metadataFilePath, transferParameters, frontend)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataFilePath" Type="System.String" />
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontend" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
      </Parameters>
      <Docs>
        <param name="metadataFilePath">Der Dateipfad, auf diese Metadatendatei (für das Speichern von Zwecke) zugewiesen werden soll.</param>
        <param name="transferParameters">Die Parameter zum Erstellen dieser Metadaten verwendet werden soll.</param>
        <param name="frontend">Das Front-End zu verwendende pro Dateimetadaten generiert werden soll.</param>
        <summary>
            Erstellt ein neues TransferFolderMetadata-Objekt aus der angegebenen Parameter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferFolderMetadata.DeleteFile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Löscht die Metadatendatei vom Datenträger.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">MetadataFilePath von NULL oder leer sein. Metadaten können nicht gelöscht werden, bis diese Eigenschaft festgelegt wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public int FileCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FileCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, der Anzahl der Dateien in dieser Übertragung fest.
            </summary>
        <value>
            Die Segmentanzahl.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As TransferMetadata()" />
      <MemberSignature Language="F#" Value="member this.Files : Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Zeiger auf ein Array von Dateimetadaten für die Übertragung an. Dies wird für jede Datei verwendet, das übertragen wird.
            </summary>
        <value>
            Die Segmente.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFolderPath">
      <MemberSignature Language="C#" Value="public string InputFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.InputFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des vollständigen Pfads zu der Datei, die übertragen werden.
            </summary>
        <value>
            Der Pfad der Eingabedatei.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsRecursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, ob Recurisve Directory Übertragung oder eine Flatfile Verzeichnis übertragen sieht
            </summary>
        <value>
          <c>"true"</c> Wenn diese Instanz rekursive; andernfalls <c>"false"</c>.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Save">
      <MemberSignature Language="C#" Value="public void Save ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Save() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Save" />
      <MemberSignature Language="VB.NET" Value="Public Sub Save ()" />
      <MemberSignature Language="F#" Value="member this.Save : unit -&gt; unit" Usage="transferFolderMetadata.Save " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Speichert die angegebenen Metadaten an den kanonischen Speicherort an. Diese Methode ist threadsicher.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamFolderPath">
      <MemberSignature Language="C#" Value="public string TargetStreamFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des vollständige Stream Ordnerpfad, der als Stammverzeichnis für alle Dateien und Ordner übertragenen verwendet wird.
            </summary>
        <value>
            Der Zielpfad Stream.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileBytes">
      <MemberSignature Language="C#" Value="public long TotalFileBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalFileBytes As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileBytes : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TotalFileBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Bytes für alle Dateien.
            </summary>
        <value>
            Die Gesamtanzahl der Bytes für alle Dateien.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TransferId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, des eindeutigen Bezeichners dieser Übertragung zugeordnet.
            </summary>
        <value>
            Der Transfer-Bezeichner.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>