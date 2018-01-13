<Type Name="ExeHostEntryPointDescription" FullName="System.Fabric.Description.ExeHostEntryPointDescription">
  <TypeSignature Language="C#" Value="public sealed class ExeHostEntryPointDescription : System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExeHostEntryPointDescription extends System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ExeHostEntryPointDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExeHostEntryPointDescription&#xA;Inherits EntryPointDescription" />
  <TypeSignature Language="F#" Value="type ExeHostEntryPointDescription = class&#xA;    inherit EntryPointDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.EntryPointDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Enthält Informationen zu den ausführbaren Einstiegspunkt.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public string Arguments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Arguments" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Arguments As String" />
      <MemberSignature Language="F#" Value="member this.Arguments : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Argumente an die ausführbare Datei im Dienstmanifest gemäß. </para>
        </summary>
        <value>
          <para>Die Argumente, die entsprechend den Angaben in das Dienstmanifest an die ausführbare Datei übergeben werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionEnabled">
      <MemberSignature Language="C#" Value="public bool ConsoleRedirectionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsoleRedirectionEnabled" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionEnabled : bool" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
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
          <para>Ruft ab oder legt einen Wert, der angibt, ob aktiviert oder deaktiviert die Umleitung der Konsole für ausführbare Dateien fest. Die Standardeinstellung lautet <languageKeyword>false</languageKeyword>.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> So aktivieren Sie die Umleitung der Konsole für ausführbare Dateien; andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileMaxSizeInKb">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileMaxSizeInKb { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileMaxSizeInKb As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileMaxSizeInKb : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Größe in KB für Umleitung Konsolendatei fest.</para>
        </summary>
        <value>
          <para>Die maximale Größe in KB für Umleitung Konsolendatei.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileRetentionCount">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileRetentionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileRetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileRetentionCount : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die maximale Anzahl von Dateien für die Umleitung der Konsole vor dem Überschreiben von Inhalten in zirkulär. </para>
        </summary>
        <value>
          <para>Die maximale Anzahl von Dateien, die für die Umleitung der Konsole vor dem Überschreiben von Inhalt in einer kreisförmigen Weise verwendet werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeriodicInterval">
      <MemberSignature Language="C#" Value="public long PeriodicInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PeriodicInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeriodicInterval As Long" />
      <MemberSignature Language="F#" Value="member this.PeriodicInterval : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Zeitraum fest, wenn die ausführbare Datei muss in regelmäßigen Abständen aktiviert werden. </para>
        </summary>
        <value>
          <para>Der Zeitraum muss die ausführbare Datei in regelmäßigen Abständen aktiviert werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Program">
      <MemberSignature Language="C#" Value="public string Program { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Program" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Program" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Program As String" />
      <MemberSignature Language="F#" Value="member this.Program : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Program" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Namen der ausführbaren Datei entsprechend den Angaben in das Manifest.</para>
        </summary>
        <value>
          <para>Namen der ausführbaren Datei entsprechend den Angaben in das Manifest.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ExeHostEntryPointDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="exeHostEntryPointDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die Zeichenfolgendarstellung dieser Einstiegspunkt ab.</para>
        </summary>
        <returns>
          <para>Die Zeichenfolgendarstellung dieser Einstiegspunkt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkingFolder">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ExeHostWorkingFolder WorkingFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ExeHostWorkingFolder WorkingFolder" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkingFolder As ExeHostWorkingFolder" />
      <MemberSignature Language="F#" Value="member this.WorkingFolder : System.Fabric.Description.ExeHostWorkingFolder" Usage="System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder festlegen den Arbeitsordner für die ausführbare Datei entsprechend den Angaben in das Manifest.</para>
        </summary>
        <value>
          <para>Der Arbeitsordner für die ausführbare Datei entsprechend den Angaben in das Manifest.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>