<Type Name="BatchAccount" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccount">
  <TypeSignature Language="C#" Value="public class BatchAccount : Microsoft.Azure.Management.Batch.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccount extends Microsoft.Azure.Management.Batch.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BatchAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält Informationen zu einem Azure Batch-Konto an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BatchAccount-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccount (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string accountEndpoint = null, Microsoft.Azure.Management.Batch.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Models.ProvisioningState.Invalid, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode = null, Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference = null, Microsoft.Azure.Management.Batch.Models.AutoStorageProperties autoStorage = null, int dedicatedCoreQuota = 0, int lowPriorityCoreQuota = 0, int poolQuota = 0, int activeJobAndJobScheduleQuota = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string accountEndpoint, valuetype Microsoft.Azure.Management.Batch.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode, class Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference, class Microsoft.Azure.Management.Batch.Models.AutoStorageProperties autoStorage, int32 dedicatedCoreQuota, int32 lowPriorityCoreQuota, int32 poolQuota, int32 activeJobAndJobScheduleQuota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Batch.Models.ProvisioningState,System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolAllocationMode},Microsoft.Azure.Management.Batch.Models.KeyVaultReference,Microsoft.Azure.Management.Batch.Models.AutoStorageProperties,System.Int32,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccount : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Batch.Models.ProvisioningState * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; * Microsoft.Azure.Management.Batch.Models.KeyVaultReference * Microsoft.Azure.Management.Batch.Models.AutoStorageProperties * int * int * int * int -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccount (id, name, type, location, tags, accountEndpoint, provisioningState, poolAllocationMode, keyVaultReference, autoStorage, dedicatedCoreQuota, lowPriorityCoreQuota, poolQuota, activeJobAndJobScheduleQuota)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accountEndpoint" Type="System.String" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Models.ProvisioningState" />
        <Parameter Name="poolAllocationMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;" />
        <Parameter Name="keyVaultReference" Type="Microsoft.Azure.Management.Batch.Models.KeyVaultReference" />
        <Parameter Name="autoStorage" Type="Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" />
        <Parameter Name="dedicatedCoreQuota" Type="System.Int32" />
        <Parameter Name="lowPriorityCoreQuota" Type="System.Int32" />
        <Parameter Name="poolQuota" Type="System.Int32" />
        <Parameter Name="activeJobAndJobScheduleQuota" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="id">Die ID der Ressource.</param>
        <param name="name">Der Name der Ressource.</param>
        <param name="type">Der Typ der Ressource.</param>
        <param name="location">Der Speicherort der Ressource.</param>
        <param name="tags">Die Tags der Ressource.</param>
        <param name="accountEndpoint">Der Konto-Endpunkt für die Interaktion mit der Batch-Dienst verwendet.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der Ressource. Folgende Werte sind möglich: "Ungültig", "erstellen", "Löschen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</param>
        <param name="poolAllocationMode">Der Modus der Zuordnung zum Erstellen von Pools im Batch-Konto verwendet werden soll.</param>
        <param name="keyVaultReference">Ein Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.</param>
        <param name="autoStorage">Die Eigenschaften und den Status jedes Auto-Storage-Kontos das Batch-Konto zugeordnet.</param>
        <param name="dedicatedCoreQuota">Das Kontingent des dedizierten Kern für dieses Batch-Konto.</param>
        <param name="lowPriorityCoreQuota">Die mit niedriger Priorität kernkontingent für dieses Batch-Konto.</param>
        <param name="poolQuota">Das poolkontingent für dieses Batch-Konto.</param>
        <param name="activeJobAndJobScheduleQuota">Die aktiven Auftrag und die Auftrag-Zeitplan-Kontingent für dieses Batch-Konto.</param>
        <summary>
            Initialisiert eine neue Instanz der BatchAccount-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountEndpoint">
      <MemberSignature Language="C#" Value="public string AccountEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.AccountEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.AccountEndpoint : string" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.AccountEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Interaktion mit der Batch-Dienst-Endpunkt ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveJobAndJobScheduleQuota">
      <MemberSignature Language="C#" Value="public int ActiveJobAndJobScheduleQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveJobAndJobScheduleQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.ActiveJobAndJobScheduleQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeJobAndJobScheduleQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktiven Auftrag und den Auftrag-Zeitplan-Kontingent für dieses Batch-Konto ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoStorageProperties AutoStorage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoStorageProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoStorage As AutoStorageProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.AutoStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoStorageProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Eigenschaften und den Status jedes Auto-Storage-Kontos das Batch-Konto zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DedicatedCoreQuota">
      <MemberSignature Language="C#" Value="public int DedicatedCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DedicatedCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.DedicatedCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DedicatedCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.DedicatedCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dedicatedCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die dedizierten kernkontingent für dieses Batch-Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.KeyVaultReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultReference As KeyVaultReference" />
      <MemberSignature Language="F#" Value="member this.KeyVaultReference : Microsoft.Azure.Management.Batch.Models.KeyVaultReference" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.KeyVaultReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.KeyVaultReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowPriorityCoreQuota">
      <MemberSignature Language="C#" Value="public int LowPriorityCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LowPriorityCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.LowPriorityCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LowPriorityCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.LowPriorityCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.LowPriorityCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lowPriorityCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Kontingent der Kerne mit niedriger Priorität für dieses Batch-Konto ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolAllocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolAllocationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolAllocationMode As Nullable(Of PoolAllocationMode)" />
      <MemberSignature Language="F#" Value="member this.PoolAllocationMode : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolAllocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolAllocationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Allocation-Modus zum Erstellen von Pools im Batch-Konto verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "BatchService", "UserSubscription"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolQuota">
      <MemberSignature Language="C#" Value="public int PoolQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PoolQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.PoolQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das poolkontingent für dieses Batch-Konto ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus der Ressource ab. Folgende Werte sind möglich: "Ungültig", "erstellen", "Löschen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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