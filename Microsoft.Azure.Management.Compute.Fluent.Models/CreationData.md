<Type Name="CreationData" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData">
  <TypeSignature Language="C#" Value="public class CreationData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreationData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" />
  <TypeSignature Language="VB.NET" Value="Public Class CreationData" />
  <TypeSignature Language="F#" Value="type CreationData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Daten, die beim Erstellen eines Datenträgers verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CreationData-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationData (Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption createOption, string storageAccountId = null, Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference imageReference = null, string sourceUri = null, string sourceResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption createOption, string storageAccountId, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference imageReference, string sourceUri, string sourceResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOption, Optional storageAccountId As String = null, Optional imageReference As ImageDiskReference = null, Optional sourceUri As String = null, Optional sourceResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationData : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption * string * Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationData (createOption, storageAccountId, imageReference, sourceUri, sourceResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference" />
        <Parameter Name="sourceUri" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createOption">Folgende Werte sind möglich: "Leer", "Anfügen", "FromImage", "Import", "Kopieren", "Wiederherstellen"</param>
        <param name="storageAccountId">Wenn CreateOption importieren Sie, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren. Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.</param>
        <param name="imageReference">Datenträger-Quellinformationen.</param>
        <param name="sourceUri">Wenn CreationOption importieren, ist dies eine SAS-URI in ein Blob in einen verwalteten Datenträger importiert werden sollen. Wenn CreationOption Kopie ist, ist dies ein relativer Uri ist, enthält die Id der Momentaufnahme für die Datenquelle an einen verwalteten Datenträger kopiert werden.</param>
        <param name="sourceResourceId">Wenn CreateOption Kopie ist, ist dies die ARM-Id der Quellmomentaufnahme oder des Datenträgers an. Wenn CreationOption Wiederherstellung ist, ist dies die ARM-ähnliche-Id von der Quelle Datenträger-Wiederherstellungspunkt an.</param>
        <summary>
            Initialisiert eine neue Instanz der CreationData-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOption" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt folgende Werte möglich sind: "Leer", "Anfügen", "FromImage", "Import", "Kopieren", "Wiederherstellen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageDiskReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Datenträger Quellinformationen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob CreateOption Kopie ist dies ist die ARM-Id der Quellmomentaufnahme oder des Datenträgers. Wenn CreationOption Wiederherstellung ist, ist dies die ARM-ähnliche-Id von der Quelle Datenträger-Wiederherstellungspunkt an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUri">
      <MemberSignature Language="C#" Value="public string SourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceUri As String" />
      <MemberSignature Language="F#" Value="member this.SourceUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.SourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob CreationOption Import ist, ist dies eine SAS-URI in ein Blob in einen verwalteten Datenträger importiert werden sollen. Wenn CreationOption Kopie ist, ist dies ein relativer Uri ist, enthält die Id der Momentaufnahme für die Datenquelle an einen verwalteten Datenträger kopiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, wenn CreateOption importieren, den Azure Resource Manager-Bezeichner des Speicherkontos mit dem Blob als Datenträger importieren. Nur erforderlich, wenn das Blob in einem anderen Abonnement befindet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="creationData.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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