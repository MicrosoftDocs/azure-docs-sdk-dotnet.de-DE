<Type Name="KeyValueStoreReplicaSettings" FullName="System.Fabric.KeyValueStoreReplicaSettings">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplicaSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplicaSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplicaSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplicaSettings" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplicaSettings = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Einstellungen für ein Replikat des Schlüssel/Wert-Speicher dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplicaSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplicaSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.KeyValueStoreReplicaSettings" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCopyNotificationPrefetch">
      <MemberSignature Language="C#" Value="public bool EnableCopyNotificationPrefetch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableCopyNotificationPrefetch" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.EnableCopyNotificationPrefetch" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCopyNotificationPrefetch As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableCopyNotificationPrefetch : bool with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.EnableCopyNotificationPrefetch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Datenbank während der öffnen prefetch fest.
            </summary>
        <value>
            Gibt "true" zurück, wenn aktiviert, andernfalls False.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullCopyMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.FullCopyMode FullCopyMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/FullCopyMode FullCopyMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.FullCopyMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FullCopyMode As KeyValueStoreReplica.FullCopyMode" />
      <MemberSignature Language="F#" Value="member this.FullCopyMode : System.Fabric.KeyValueStoreReplica.FullCopyMode with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.FullCopyMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+FullCopyMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, die vollständige Kopiermodus beim Erstellen der sekundären Replikate. <see cref="T:System.Fabric.KeyValueStoreReplica.FullCopyMode" /></summary>
        <value>
            Gibt den Modus für die vollständige Kopie zurück.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogTruncationIntervalInMinutes">
      <MemberSignature Language="C#" Value="public int LogTruncationIntervalInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogTruncationIntervalInMinutes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.LogTruncationIntervalInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property LogTruncationIntervalInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.LogTruncationIntervalInMinutes : int with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.LogTruncationIntervalInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall fest, nach dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> versucht, lokale truncate speichern Protokolle aus, wenn lokale Geschäft hat <see cref="P:System.Fabric.LocalEseStoreSettings.EnableIncrementalBackup" /> aktiviert und keine Sicherung wurde vom Benutzer initiiert wurden, während dieses Intervalls.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryNotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode SecondaryNotificationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode SecondaryNotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.SecondaryNotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryNotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.SecondaryNotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.SecondaryNotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, die sekundären Benachrichtigungsmodus zu aktivieren. <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /></summary>
        <value>
            Gibt die sekundären Benachrichtigungsmodus zurück.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionDrainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan TransactionDrainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TransactionDrainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplicaSettings.TransactionDrainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property TransactionDrainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TransactionDrainTimeout : TimeSpan with get, set" Usage="System.Fabric.KeyValueStoreReplicaSettings.TransactionDrainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, der Zeitspanne, die ausstehende Transaktionen ausgleichen während der Herabstufung von der primären Rolle, bevor der Hostprozess beendet wird.
            </summary>
        <value>
            Gibt das Timeout ausgleichen.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>