<Type Name="CorrelationFilter" FullName="Microsoft.Azure.ServiceBus.CorrelationFilter">
  <TypeSignature Language="C#" Value="public sealed class CorrelationFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorrelationFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorrelationFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt den Filterausdruck für die Korrelation dar.
            </summary>
    <remarks>
      <para>
            Eine CorrelationFilter enthält eine Reihe von Bedingungen, die mit einem oder mehreren der Benutzer- und Systemeigenschaften einer eingehenden Nachricht abgeglichen werden.
            Eine übliche Verwendung wird eine Übereinstimmung für die <see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" /> -Eigenschaft, die Anwendung jedoch auch die Möglichkeit, für den Vergleich <see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />, und ein beliebiger Benutzerdefinierte Eigenschaften.
            Eine Übereinstimmung liegt vor, wenn der Wert einer Eigenschaft einer eingehenden Nachricht gleich dem im Korrelationsfilter angegebenen Wert ist. Für Zeichenfolgenausdrücke wird beim Vergleich die Groß-/Kleinschreibung beachtet. Wenn Sie mehrere Übereinstimmung Eigenschaften angeben, fasst der Filter als einer logischen AND-Bedingung, was bedeutet, dass alle Bedingungen für den Filter entsprechend übereinstimmen müssen.
            </para>
      <para>
            Die CorrelationFilter verfügt über eine effiziente Tastenkombination für Deklarationen von Filtern, die nur mit Korrelation auf Gleichheit.
            In diesem Fall kann die Kosten der Lexigraphical Analyse des Ausdrucks vermieden werden.
            Nicht nur werden zum Zeitpunkt der Deklaration korrelationsfilter optimiert werden, sondern wird auch zur Laufzeit optimiert werden.
            Korrelationszuordnung Filter kann auf eine Hashtabelle Suche reduziert werden die die Komplexität des Satzes von definierten korrelationsfilter aus, die o(1)-Einfüge-aggregiert.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />-Klasse mit Standardwerten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (correlationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.CorrelationFilter : string -&gt; Microsoft.Azure.ServiceBus.CorrelationFilter" Usage="new Microsoft.Azure.ServiceBus.CorrelationFilter correlationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="correlationId">Der Bezeichner für die Korrelation.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> -Klasse mit der angegebenen Korrelations-ID.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die <paramref name="correlationId" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Inhaltstyp der Nachricht.
            </summary>
        <value>Der Inhaltstyp der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ID der Korrelation
            </summary>
        <value>Der Bezeichner der Korrelation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Anwendungsspezifische Bezeichnung.
            </summary>
        <value>Die anwendungsspezifische Bezeichnung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Bezeichner der Nachricht.
            </summary>
        <value>Der Bezeichner der Nachricht.</value>
        <remarks>Max. MessageId-Größe beträgt 128 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Anwendungsspezifische Eigenschaften der Nachricht.
            </summary>
        <value>Die Anwendung spezifischen Eigenschaften der Nachricht.</value>
        <remarks>
            Nur nach Wert Typen werden unterstützt: Byte, Sbyte, Char, Short, Ushort, Int, "uint", long, Ulong, Float, double, Decimal, Bool, Guid, Zeichenfolge, Uri, "DateTime", "DateTimeOffset", TimeSpan, Stream, Byte [] und IList / IDictionary von unterstützte Typen
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Warteschlangenadresse für die Antwort.
            </summary>
        <value>Die Adresse der Warteschlange, an die geantwortet werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sitzungs-ID, um zu antworten.
            </summary>
        <value>Die Sitzungs-ID, an die geantwortet werden soll.</value>
        <remarks>Max. Größe der ReplyToSessionId ist 128.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sitzungs-ID.
            </summary>
        <value>Die Sitzungs-ID.</value>
        <remarks>Max. Größe der SessionId beträgt 128 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Zieladresse.
            </summary>
        <value>Die Adresse an.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="correlationFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Konvertiert den Wert der aktuellen Instanz in die entsprechende Zeichenfolgendarstellung.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der aktuellen Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>