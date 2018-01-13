<Type Name="IaasVMRecoveryPoint" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint">
  <TypeSignature Language="C#" Value="public class IaasVMRecoveryPoint : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaasVMRecoveryPoint extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint" />
  <TypeSignature Language="VB.NET" Value="Public Class IaasVMRecoveryPoint&#xA;Inherits RecoveryPoint" />
  <TypeSignature Language="F#" Value="type IaasVMRecoveryPoint = class&#xA;    inherit RecoveryPoint" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IaaS-VM arbeitsauslastung bestimmte Sicherungskopie.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRecoveryPoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IaasVMRecoveryPoint-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRecoveryPoint (string recoveryPointType = null, Nullable&lt;DateTime&gt; recoveryPointTime = null, string recoveryPointAdditionalInfo = null, string sourceVMStorageType = null, Nullable&lt;bool&gt; isSourceVMEncrypted = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails keyAndSecret = null, Nullable&lt;bool&gt; isInstantILRSessionActive = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; recoveryPointTierDetails = null, Nullable&lt;bool&gt; isManagedVirtualMachine = null, string virtualMachineSize = null, Nullable&lt;bool&gt; originalStorageAccountOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string recoveryPointType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; recoveryPointTime, string recoveryPointAdditionalInfo, string sourceVMStorageType, valuetype System.Nullable`1&lt;bool&gt; isSourceVMEncrypted, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails keyAndSecret, valuetype System.Nullable`1&lt;bool&gt; isInstantILRSessionActive, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; recoveryPointTierDetails, valuetype System.Nullable`1&lt;bool&gt; isManagedVirtualMachine, string virtualMachineSize, valuetype System.Nullable`1&lt;bool&gt; originalStorageAccountOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation},System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recoveryPointType As String = null, Optional recoveryPointTime As Nullable(Of DateTime) = null, Optional recoveryPointAdditionalInfo As String = null, Optional sourceVMStorageType As String = null, Optional isSourceVMEncrypted As Nullable(Of Boolean) = null, Optional keyAndSecret As KeyAndSecretDetails = null, Optional isInstantILRSessionActive As Nullable(Of Boolean) = null, Optional recoveryPointTierDetails As IList(Of RecoveryPointTierInformation) = null, Optional isManagedVirtualMachine As Nullable(Of Boolean) = null, Optional virtualMachineSize As String = null, Optional originalStorageAccountOption As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint : string * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint (recoveryPointType, recoveryPointTime, recoveryPointAdditionalInfo, sourceVMStorageType, isSourceVMEncrypted, keyAndSecret, isInstantILRSessionActive, recoveryPointTierDetails, isManagedVirtualMachine, virtualMachineSize, originalStorageAccountOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryPointType" Type="System.String" />
        <Parameter Name="recoveryPointTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryPointAdditionalInfo" Type="System.String" />
        <Parameter Name="sourceVMStorageType" Type="System.String" />
        <Parameter Name="isSourceVMEncrypted" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAndSecret" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails" />
        <Parameter Name="isInstantILRSessionActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoveryPointTierDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt;" />
        <Parameter Name="isManagedVirtualMachine" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="originalStorageAccountOption" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="recoveryPointType">Der Typ der Sicherungskopie.</param>
        <param name="recoveryPointTime">Zeitpunkt, zu dem dieser Sicherungskopie erstellt wurde.</param>
        <param name="recoveryPointAdditionalInfo">Zusätzliche Informationen, die dieser Sicherungskopie zugeordnet werden.</param>
        <param name="sourceVMStorageType">Der Speichertyp des virtuellen Computers, dessen Sicherungskopie erstellt wird.</param>
        <param name="isSourceVMEncrypted">Bestimmt, ob der virtuelle Computer verschlüsselt wurde, wenn die Sicherungskopie erstellt wird.</param>
        <param name="keyAndSecret">Erforderlichen Details für die Wiederherstellung einer verschlüsselte-VM. Gilt nur, wenn IsSourceVMEncrypted auf "true" festgelegt ist.</param>
        <param name="isInstantILRSessionActive">Ist die Sitzung zum Wiederherstellen von Elementen aus dieser Sicherungskopie weiterhin aktiv ist.</param>
        <param name="recoveryPointTierDetails">Punkt-Tier-Wiederherstellungsinformationen.</param>
        <param name="isManagedVirtualMachine">Gibt an, ob der virtuelle Computer mit Datenträger verwaltet ist</param>
        <param name="virtualMachineSize">VM-Größe</param>
        <param name="originalStorageAccountOption">Original-SA-Option</param>
        <summary>
            Initialisiert eine neue Instanz der IaasVMRecoveryPoint-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInstantILRSessionActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsInstantILRSessionActive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsInstantILRSessionActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsInstantILRSessionActive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsInstantILRSessionActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsInstantILRSessionActive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsInstantILRSessionActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isInstantILRSessionActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest ist die Sitzung zum Wiederherstellen von Elementen aus dieser Sicherungskopie weiterhin aktiv ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedVirtualMachine">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsManagedVirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsManagedVirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsManagedVirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property IsManagedVirtualMachine As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsManagedVirtualMachine : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsManagedVirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isManagedVirtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der virtuelle Computer mit Datenträger verwaltet wird
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSourceVMEncrypted">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSourceVMEncrypted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSourceVMEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsSourceVMEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSourceVMEncrypted As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSourceVMEncrypted : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.IsSourceVMEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSourceVMEncrypted")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt identifiziert, ob der virtuelle Computer verschlüsselt wurde, wenn die Sicherungskopie erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyAndSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails KeyAndSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails KeyAndSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.KeyAndSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyAndSecret As KeyAndSecretDetails" />
      <MemberSignature Language="F#" Value="member this.KeyAndSecret : Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.KeyAndSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyAndSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.KeyAndSecretDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest erforderlichen Details für die Wiederherstellung einer verschlüsselte-VM.
            Gilt nur, wenn IsSourceVMEncrypted auf "true" festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalStorageAccountOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OriginalStorageAccountOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OriginalStorageAccountOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.OriginalStorageAccountOption" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalStorageAccountOption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OriginalStorageAccountOption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.OriginalStorageAccountOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="originalStorageAccountOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest ursprünglichen SA-Option
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointAdditionalInfo">
      <MemberSignature Language="C#" Value="public string RecoveryPointAdditionalInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointAdditionalInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointAdditionalInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointAdditionalInfo As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointAdditionalInfo : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointAdditionalInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointAdditionalInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert zusätzlichen Informationen, die mit dieser Sicherungskopie verknüpft ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointTierDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; RecoveryPointTierDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; RecoveryPointTierDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointTierDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointTierDetails As IList(Of RecoveryPointTierInformation)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointTierDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointTierDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointTierDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Wiederherstellungsinformationen für Punkt-Ebene.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RecoveryPointTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RecoveryPointTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Zeitpunkt, zu dem dieser Sicherungskopie erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointType">
      <MemberSignature Language="C#" Value="public string RecoveryPointType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointType As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.RecoveryPointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest die Sicherungskopie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVMStorageType">
      <MemberSignature Language="C#" Value="public string SourceVMStorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceVMStorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.SourceVMStorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVMStorageType As String" />
      <MemberSignature Language="F#" Value="member this.SourceVMStorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.SourceVMStorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVMStorageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Speichertyp des virtuellen Computers, dessen Sicherungskopie erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRecoveryPoint.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die VM-Größe
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>