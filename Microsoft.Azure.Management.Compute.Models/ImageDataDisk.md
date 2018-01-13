<Type Name="ImageDataDisk" FullName="Microsoft.Azure.Management.Compute.Models.ImageDataDisk">
  <TypeSignature Language="C#" Value="public class ImageDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageDataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageDataDisk" />
  <TypeSignature Language="F#" Value="type ImageDataDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt einen Datenträger an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ImageDataDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDataDisk (int lun, Microsoft.Azure.Management.Compute.Models.SubResource snapshot = null, Microsoft.Azure.Management.Compute.Models.SubResource managedDisk = null, string blobUri = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, class Microsoft.Azure.Management.Compute.Models.SubResource snapshot, class Microsoft.Azure.Management.Compute.Models.SubResource managedDisk, string blobUri, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.#ctor(System.Int32,Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, Optional snapshot As SubResource = null, Optional managedDisk As SubResource = null, Optional blobUri As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageDataDisk : int * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.SubResource * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ImageDataDisk" Usage="new Microsoft.Azure.Management.Compute.Models.ImageDataDisk (lun, snapshot, managedDisk, blobUri, caching, diskSizeGB, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="lun">Gibt die logische Gerätenummer des Datenträgers an. Dieser Wert wird verwendet, um die Datenträger für Daten innerhalb des virtuellen Computers zu identifizieren und muss daher für jede an einen virtuellen Computer angefügten Datenträger eindeutig sein.</param>
        <param name="snapshot">Der Momentaufnahme.</param>
        <param name="managedDisk">Die ManagedDisk.</param>
        <param name="blobUri">Die virtuelle Festplatte.</param>
        <param name="caching">Gibt die cacheanforderungen an.
            &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; **keine** &lt;Br&gt; &lt; Brasilien&gt; **ReadOnly** &lt;Br&gt;&lt;Br&gt; **ReadWrite** &lt;Br&gt; &lt;Br&gt; Default: **None für Standard-Speicher. ReadOnly für Premium-Speicher**. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</param>
        <param name="diskSizeGB">Gibt die Größe der leere Datenträger in Gigabyte an. Dieses Element kann verwendet werden, um den Namen des Datenträgers in Abbild eines virtuellen Computers zu überschreiben. &lt;Brasilien&gt;&lt;Br&gt; dieser Wert darf nicht größer als 1023 GB sein</param>
        <param name="storageAccountType">Gibt den Typ des Speicher-Konto für den verwalteten Datenträger. Mögliche Werte sind: Standard_LRS oder "premium_lrs". Folgende Werte sind möglich: "Standard_LRS", "premium_lrs" ""</param>
        <summary>
            Initialisiert eine neue Instanz der ImageDataDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.BlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die virtuelle Festplatte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die cacheanforderungen an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Keine** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **ReadOnly** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **ReadWrite** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Standard: **None für Standard-Speicher. ReadOnly für Premium-Speicher**. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Größe der leere Datenträger in Gigabyte an.
            Dieses Element kann verwendet werden, um den Namen des Datenträgers in Abbild eines virtuellen Computers zu überschreiben. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Dieser Wert darf nicht größer als 1023 GB sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die logische Gerätenummer des Datenträgers an.
            Dieser Wert wird verwendet, um die Datenträger für Daten innerhalb des virtuellen Computers zu identifizieren und muss daher für jede an einen virtuellen Computer angefügten Datenträger eindeutig sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As SubResource" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ManagedDisk.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource Snapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource Snapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property Snapshot As SubResource" />
      <MemberSignature Language="F#" Value="member this.Snapshot : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Snapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="snapshot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Momentaufnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt der speicherkontotyp für den verwalteten Datenträger an. Mögliche Werte sind: Standard_LRS oder "premium_lrs". Folgende Werte sind möglich: "Standard_LRS", "premium_lrs" ""
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageDataDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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