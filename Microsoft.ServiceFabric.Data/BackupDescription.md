<Type Name="BackupDescription" FullName="Microsoft.ServiceFabric.Data.BackupDescription">
  <TypeSignature Language="C#" Value="public struct BackupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit BackupDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure BackupDescription" />
  <TypeSignature Language="F#" Value="type BackupDescription = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine BackupDescription enthält alle Informationen zum Sichern eines zustandsbehafteten dienstreplikats erforderlich. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription backupCallback" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">
            Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner erstellt und lokal vom System aufgefüllt wurde. Dieser Ordner kann jetzt aus dem Knoten verschoben werden.
            </param>
        <summary>
            Initialisiert eine neue Instanz der <cref name="BackupDescription" />-Struktur.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Microsoft.ServiceFabric.Data.BackupOption option, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.BackupOption option, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(Microsoft.ServiceFabric.Data.BackupOption,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (option As BackupOption, backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Microsoft.ServiceFabric.Data.BackupOption * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription (option, backupCallback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">
            Die <cref name="BackupOption" /> für die Sicherung.
            </param>
        <param name="backupCallback">
            Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.
            </param>
        <summary>
            Initialisiert eine neue Instanz der <cref name="BackupDescription" />-Struktur.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; BackupCallback { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; BackupCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.BackupCallback : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, der Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.
            </summary>
        <value>
            Die Sicherung Rückruffunktion, die häufig verwendet, um den Sicherungsordner in einem externen Speicherort zu kopieren.
            </value>
        <remarks>
            Backup Rückruffunktion nimmt in einem BackupInfo und der Abbruch und gibt eine Aufgabe, die Verarbeitung von Sicherungsordner darstellt.
            Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.
            Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.
            Darüber hinaus wird Sicherung als fehlgeschlagen markiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Option">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupOption Option { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupOption Option" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Option As BackupOption" />
      <MemberSignature Language="F#" Value="member this.Option : Microsoft.ServiceFabric.Data.BackupOption" Usage="Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Typ der Sicherung ausführen.
            </summary>
        <value>
            Der Typ der Sicherung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>