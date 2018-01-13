<Type Name="DataDisks" FullName="Microsoft.Azure.Management.BatchAI.Models.DataDisks">
  <TypeSignature Language="C#" Value="public class DataDisks" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisks extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisks" />
  <TypeSignature Language="F#" Value="type DataDisks = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einstellungen für den Datenträger, der für den Dateiserver erstellt würde.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisks ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataDisks-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisks (int diskSizeInGB, int diskCount, string storageAccountType, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; cachingType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 diskSizeInGB, int32 diskCount, string storageAccountType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.#ctor(System.Int32,System.Int32,System.String,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (diskSizeInGB As Integer, diskCount As Integer, storageAccountType As String, Optional cachingType As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.DataDisks : int * int * string * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.DataDisks" Usage="new Microsoft.Azure.Management.BatchAI.Models.DataDisks (diskSizeInGB, diskCount, storageAccountType, cachingType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="diskSizeInGB" Type="System.Int32" />
        <Parameter Name="diskCount" Type="System.Int32" />
        <Parameter Name="storageAccountType" Type="System.String" />
        <Parameter Name="cachingType" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="diskSizeInGB">Anfängliche Festplattengröße in GB für leere Datenträger, und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Datenträger.</param>
        <param name="diskCount">Die Anzahl der Datenträger mit dem virtuellen Computer angefügt werden. RAID-Stufe 0 wird im Fall von mehreren Datenträgern angewendet werden.</param>
        <param name="storageAccountType">Gibt den Typ des Speicherkontos für den Datenträger verwendet werden soll. Mögliche Werte sind: Standard_LRS oder "premium_lrs".</param>
        <param name="cachingType">Keine "," schreibgeschützt, Lese-/Schreibmodus. Standardwert ist None. Diese Eigenschaft ist nicht patchfähigen.</param>
        <summary>
            Initialisiert eine neue Instanz der DataDisks-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CachingType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; CachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.CachingType&gt; CachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.CachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CachingType As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.CachingType : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.CachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cachingType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft keine "," ReadOnly, ReadWrite. Standardwert ist None. Diese Eigenschaft ist nicht patchfähigen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "none", "Readonly", "Readwrite"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskCount">
      <MemberSignature Language="C#" Value="public int DiskCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Datenträger mit dem virtuellen Computer angefügt werden. RAID-Stufe 0 wird im Fall von mehreren Datenträgern angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeInGB">
      <MemberSignature Language="C#" Value="public int DiskSizeInGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeInGB : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.DiskSizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, anfängliche Festplattengröße in GB für leere Datenträger und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Datenträger.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public string StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.DataDisks.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.DataDisks.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Typ des Speicherkontos für den Datenträger verwendet werden soll. Mögliche Werte sind: Standard_LRS oder "premium_lrs".
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Standard_LRS", "premium_lrs" ""
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.DataDisks.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisks.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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