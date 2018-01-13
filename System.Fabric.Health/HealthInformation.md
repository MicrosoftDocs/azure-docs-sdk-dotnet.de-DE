<Type Name="HealthInformation" FullName="System.Fabric.Health.HealthInformation">
  <TypeSignature Language="C#" Value="public sealed class HealthInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthInformation" />
  <TypeSignature Language="F#" Value="type HealthInformation = class" />
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
      <para>Stellt die allgemeine Integrität Berichtsinformationen dar.
            Es ist in allen Integritätsberichte im Health Store gesendet und in allen integritätsereignisse integritätsabfragen zurückgegebenes enthalten.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthInformation (string sourceId, string property, System.Fabric.Health.HealthState healthState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceId, string property, valuetype System.Fabric.Health.HealthState healthState) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.#ctor(System.String,System.String,System.Fabric.Health.HealthState)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthInformation : string * string * System.Fabric.Health.HealthState -&gt; System.Fabric.Health.HealthInformation" Usage="new System.Fabric.Health.HealthInformation (sourceId, property, healthState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="property" Type="System.String" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
      </Parameters>
      <Docs>
        <param name="sourceId">
          <para>Die Quelle des Berichts. Er darf nicht <languageKeyword>null</languageKeyword> oder leer sein.
            Es kann nicht gestartet werden mit"System", also reserviertes Schlüsselwort für die reporting-Komponenten.</para>
        </param>
        <param name="property">
          <para>Die Eigenschaft des Berichts. Er darf nicht <languageKeyword>null</languageKeyword> oder leer sein.</para>
        </param>
        <param name="healthState">
          <para>Der Integritätsstatus des Berichts. Muss angegeben werden.
            Muss die <see cref="F:System.Fabric.Health.HealthState.Error" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> oder <see cref="F:System.Fabric.Health.HealthState.Ok" /> Werte.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <paramref name="property" />nicht mit <languageKeyword>null</languageKeyword>.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Angegebene <paramref name="healthState" /> wird nicht unterstützt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="AutoSequenceNumber">
      <MemberSignature Language="C#" Value="public const long AutoSequenceNumber = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 AutoSequenceNumber = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const AutoSequenceNumber As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable AutoSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Automatische log Sequence Number, eine gültige Sequenznummer vom Health Client ersetzt.
            </summary>
        <remarks>Wenn ein Integritäts-Client einen Bericht mit Auto-Sequenznummer empfängt, wird die Sequenznummer automatisch mit ein gültige Sequenznummer ersetzt.
            Die Sequenznummer ist garantiert im selben Prozess erhöhen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Health.HealthInformation.Description" />
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
          <para>Ruft ab oder legt die Beschreibung des Integritätsinformationen zu. Es stellt freien Text zum Hinzufügen von Menschen lesbare Informationen über die überwachte Bedingung verwendet.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.String" /> der beschrieben wird, die Zustandsinformationen in Menschen lesbaren Format.</para>
        </value>
        <remarks>
          <para>Die maximale Länge der Beschreibung beträgt 4096 Zeichen.
            Wenn die bereitgestellte Zeichenfolge länger ist, wird er automatisch abgeschnitten.
            Wenn abgeschnitten, enthalten die letzten Zeichen in der Beschreibung einen Marker "[abgeschnitten]", und die Größe der gesamten beträgt 4096 Zeichen.
            Das Vorhandensein des Markers gibt Benutzer an, dass Daten abgeschnitten ist aufgetreten.
            Beachten Sie, dass wenn abgeschnitten, die Beschreibung enthält weniger als 4096 Zeichen aus der ursprünglichen Zeichenfolge.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthInformation.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Integritätsstatus, der den Schweregrad der überwachten Bedingung für die Berichterstattung verwendet beschreibt.</para>
        </summary>
        <value>
          <para>Der Integritätsstatus, der den Schweregrad der überwachten Bedingung für die Berichterstattung verwendet beschreibt.</para>
        </value>
        <remarks>
          <para>
            Die zulässigen Zustände sind <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> und <see cref="F:System.Fabric.Health.HealthState.Error" />.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Property">
      <MemberSignature Language="C#" Value="public string Property { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Property" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Property" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Property As String" />
      <MemberSignature Language="F#" Value="member this.Property : string" Usage="System.Fabric.Health.HealthInformation.Property" />
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
          <para>Ruft die Eigenschaft des integritätsberichts ab.</para>
        </summary>
        <value>
          <para>Die Eigenschaft der Integritätsbericht senden. Zusammen mit den <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />, eindeutig für die Zustandsinformationen.</para>
        </value>
        <remarks>
          <para>
            Die Eigenschaft ist ein <see cref="T:System.String" /> und keiner festen-Enumeration können die Reporter Flexibilität, um den Zustand zu kategorisieren, die den Bericht ausgelöst.
            Z. B. eine Reporter mit <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "A" kann den Status der verfügbaren Datenträger auf einem Knoten überwachen, damit er "AvailableDisk"-Eigenschaft auf diesem Knoten melden kann.
            Ein reporterfehler mit <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "B" kann die Konnektivität Knoten überwachen, damit er eine Eigenschaft "Verbindungen" auf dem gleichen Knoten melden kann.
            Diese Berichte werden im Health Store als separate integritätsereignisse für den angegebenen Knoten behandelt.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveWhenExpired">
      <MemberSignature Language="C#" Value="public bool RemoveWhenExpired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveWhenExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveWhenExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveWhenExpired : bool with get, set" Usage="System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
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
          <para>Ruft ab oder legt einen Wert, der angibt, ob der Bericht aus dem Health Store entfernt wird, wenn es abläuft. Wenn auf festgelegt <languageKeyword>"false"</languageKeyword>, der Bericht so behandelt, als ein Fehler, wenn abgelaufen. <languageKeyword>"false"</languageKeyword> standardmäßig.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der Bericht aus dem Health Store entfernt werden sollen, wenn abgelaufen ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </value>
        <remarks>
          <para>Wenn Clients in regelmäßigen Abständen senden möchten, legen sie <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> <languageKeyword>"false"</languageKeyword> (Standard).
            Auf diese Weise ist die Reporter Probleme (z. b. Deadlock) und kann nicht Berichten, die Entität wird auf Fehler ausgewertet, wenn Integritätsbericht senden abläuft, und dadurch wird die Entität als flag <see cref="F:System.Fabric.Health.HealthState.Error" />.
            Periodische Integritätsdienst-Clients sollten Berichte mit höheren Häufigkeit als Gültigkeitsdauer für Verzögerungen aufgrund von Health Client Batchverarbeitung tragen gesendet wird, Transport Verzögerungen bei der Nachricht über den über das Netzwerk und die Integrität speichern, verarbeiten.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="System.Fabric.Health.HealthInformation.SequenceNumber" />
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
          <para>Ruft ab oder legt die Sequenznummer der Zustandsinformationen zum Überalterung Erkennung durch den Health Store zugeordnet.
            Muss größer sein als <see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />.</para>
        </summary>
        <value>
          <para>Die Bericht-Sequenznummer Integritätsinformationen zugeordnet werden soll.</para>
        </value>
        <remarks>
          <para>Die Sequenznummer des Berichts durch Health Store verwendet werden, um veraltete Berichte zu erkennen.
            </para>
          <para>Die meisten der Zeiten muss Reporter Geben Sie die Sequenznummer. Der Standardwert <see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" /> kann stattdessen verwendet werden. Ein Integritäts-Client einen Bericht mit Auto-Sequenznummer empfängt, wird eine gültige Sequenznummer, die sichergestellt ist, erhöhen Sie im selben Prozess generiert.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="System.Fabric.Health.HealthInformation.SourceId" />
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
          <para>Ruft den Quellnamen, der Watchdog/Systemkomponente identifiziert, die die Zustandsinformationen generiert.</para>
        </summary>
        <value>
          <para>Die Quelle des Integritätsbericht senden, das die Watchdog/Systemkomponente bezeichnet, die den Bericht erstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="System.Fabric.Health.HealthInformation.TimeToLive" />
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
          <para>Ruft ab oder legt sie fest, wie lange der Integritätsbericht gültig ist. Muss größer sein als TimeSpan.Zero sein.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.TimeSpan" /> , die Zeit für die Gültigkeitsdauer des integritätsberichts darstellt.</para>
        </value>
        <remarks>
          <para>Wenn Clients in regelmäßigen Abständen senden möchten, sollten sie Berichte mit höheren Häufigkeit als Gültigkeitsdauer senden.
            Wenn Clients auf den Übergang melden, können sie die Zeit für die Gültigkeitsdauer auf Infinite festgelegt.</para>
          <para>Ablauf der Gültigkeitsdauer der integritätsereignis, das die Zustandsinformationen enthält wird entweder entfernt aus dem Health Store, wenn <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> ist <languageKeyword>"true"</languageKeyword> oder auf Fehler, ausgewertet werden, wenn <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> ist <languageKeyword>"false"</languageKeyword>.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Der angegebene Wert war ungültig. Geben Sie eine Dauer, die größer als 0 ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthInformation.ToString " />
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
            Erstellt eine zeichenfolgenbeschreibung der Integritätsinformationen zu.
            </summary>
        <returns>Zeichenfolgenbeschreibung des Integritätsinformationen zu.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>
            Unbekannte Sequenznummer, die mit einer ungültigen Sequenznummer ist, die durch den Health Store nicht akzeptiert wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>