<Type Name="RestoreSettings" FullName="System.Fabric.RestoreSettings">
  <TypeSignature Language="C#" Value="public sealed class RestoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RestoreSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RestoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RestoreSettings" />
  <TypeSignature Language="F#" Value="type RestoreSettings = class" />
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
            Stellt die Einstellungen für ein Schlüssel/Wert-Speicher <see cref="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" /> Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.RestoreSettings" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings (bool inlineReopen);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool inlineReopen) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inlineReopen As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.RestoreSettings : bool -&gt; System.Fabric.RestoreSettings" Usage="new System.Fabric.RestoreSettings inlineReopen" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inlineReopen" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="inlineReopen">
            Gibt an, ob die <see cref="T:System.Fabric.KeyValueStoreReplica" /> sollte erneut öffnen, selbst nachdem erfolgreich aus der angegebenen Sicherung wiederhergestellt wurde. Wenn "false" angegeben ist, meldet das Replikat vorübergehenden Fehler nach der erfolgreichen Wiederherstellung an. 
            </param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.RestoreSettings" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings (bool inlineReopen, bool enableLsnCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool inlineReopen, bool enableLsnCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inlineReopen As Boolean, enableLsnCheck As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.RestoreSettings : bool * bool -&gt; System.Fabric.RestoreSettings" Usage="new System.Fabric.RestoreSettings (inlineReopen, enableLsnCheck)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inlineReopen" Type="System.Boolean" />
        <Parameter Name="enableLsnCheck" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="inlineReopen">
            Gibt an, ob die <see cref="T:System.Fabric.KeyValueStoreReplica" /> sollte erneut öffnen, selbst nachdem erfolgreich aus der angegebenen Sicherung wiederhergestellt wurde. Wenn "false" angegeben ist, meldet das Replikat vorübergehenden Fehler nach der erfolgreichen Wiederherstellung an.  
            </param>
        <param name="enableLsnCheck">
            Gibt an, ob die <see cref="T:System.Fabric.KeyValueStoreReplica" /> sollten überprüfen,  
            Wiederherstellung von Daten ist nicht älter als der Dienst derzeit vorhandenen Daten.
            Dies schützt gegen versehentliche Datenverluste. Wenn "false" angegeben ist, <see cref="T:System.Fabric.KeyValueStoreReplica" /> aktuelle Dienstdaten wird mit der Wiederherstellung von Daten überschrieben werden, selbst wenn präsentieren von Daten im Dienst in neueren. 
            </param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.RestoreSettings" />-Klasse. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableLsnCheck">
      <MemberSignature Language="C#" Value="public bool EnableLsnCheck { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableLsnCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.RestoreSettings.EnableLsnCheck" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableLsnCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableLsnCheck : bool" Usage="System.Fabric.RestoreSettings.EnableLsnCheck" />
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
            Gibt an, ob die <see cref="T:System.Fabric.KeyValueStoreReplica" /> sollten überprüfen,  
            Wiederherstellung von Daten ist nicht älter als der Dienst derzeit vorhandenen Daten.
            Dies schützt gegen versehentliche Datenverluste. Wenn "false" angegeben ist, <see cref="T:System.Fabric.KeyValueStoreReplica" /> aktuelle Dienstdaten wird mit der Wiederherstellung von Daten überschrieben werden, selbst wenn präsentieren von Daten im Dienst in neueren. 
            </summary>
        <value>
            Ein <see cref="T:System.Boolean" /> Wert gibt an, ob <see cref="T:System.Fabric.KeyValueStoreReplica" /> wird überprüft, ob die Wiederherstellung von Daten nicht älter als die Daten, die derzeit im Dienst vorhanden ist.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InlineReopen">
      <MemberSignature Language="C#" Value="public bool InlineReopen { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InlineReopen" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.RestoreSettings.InlineReopen" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InlineReopen As Boolean" />
      <MemberSignature Language="F#" Value="member this.InlineReopen : bool" Usage="System.Fabric.RestoreSettings.InlineReopen" />
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
            Gibt an, ob die <see cref="T:System.Fabric.KeyValueStoreReplica" /> sollte erneut öffnen, selbst nachdem erfolgreich aus der angegebenen Sicherung wiederhergestellt wurde. Wenn "false" angegeben ist, meldet das Replikat vorübergehenden Fehler nach der erfolgreichen Wiederherstellung an. 
            </summary>
        <value>
            Ein <see cref="T:System.Boolean" /> Wert gibt an, ob <see cref="T:System.Fabric.KeyValueStoreReplica" /> selbst wird erneut geöffnet nach der Wiederherstellung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>