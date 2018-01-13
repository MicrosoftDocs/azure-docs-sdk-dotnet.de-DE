<Type Name="PagedApplicationTypeQueryDescription" FullName="System.Fabric.Description.PagedApplicationTypeQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedApplicationTypeQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="F#" Value="type PagedApplicationTypeQueryDescription = class" />
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
      <para>Beschreibt einen Satz von Filtern, die beim Ausführen der Abfrage verwendeten <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</para>
    </summary>
    <remarks>
      <para>Die Standardwerte für diese abfragebeschreibung stellen Sie sicher, dass die Ergebnisse werden auf der ersten Seite zurückgegeben und keine Filter anwenden.
            Diese abfragebeschreibung kann durch Festlegen einzelner Eigenschaften angepasst werden.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedApplicationTypeQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeDefinitionKindFilter As ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKindFilter : System.Fabric.Description.ApplicationTypeDefinitionKindFilter with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder Festlegen der definitionsart verwendet, um die Anwendungstypen zu filtern, die zurückgegeben werden.
            </para>
        </summary>
        <value>
          <para>Die definitionsart verwendet, um die Anwendungstypen zu filtern.</para>
        </value>
        <remarks>
          <para>Wenn ApplicationTypeDefinitionKindFilter nicht angegeben ist, würde das Ergebnis nicht durch definitionsart gefiltert werden.</para>
          <para>ApplicationTypeNameFilter und ApplicationTypeDefinitionKindFilter können nicht zusammen angegeben werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
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
          <para>Ruft ab, oder legt ihn fest zum Abrufen der Details für den Anwendungstyp.</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Der Standardwert ist Null, was die Anwendungstypen übereinstimmt.
            </para>
          <para>
            Dieser Parameter entspricht, für die Groß-/Kleinschreibung beachtet genaue anwendungstypnamen im Manifest Anwendung alle bereitgestellten oder Bereitstellung Anwendungstypen definiert. Beispielsweise entspricht dem Wert "Test" nicht "TestApp", da sie nur eine teilweise Übereinstimmung ist.
            Dieser Wert dürfen nicht für die Version des Anwendungstyps und alle Versionen der gleichen Anwendung Typnamen entspricht.
            Legen Sie diesen Wert, um anzufordern, dass die Anwendungstypen nicht der Fall ist.
            </para>
          <para>
            ApplicationTypeNameFilter und ApplicationTypeDefinitionKindFilter können nicht zusammen angegeben werden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersionFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersionFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersionFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersionFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersionFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
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
          <para>
            Ruft ab oder legt die Version der Anwendung zum Abrufen der Details für.
            </para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Der Standardwert ist Null, das alle für die Anwendung übereinstimmt, geben Sie Versionen von einer bestimmten Anwendung Type-Name. Dieser Filter sollte bereitgestellt werden, nur, wenn eine Anwendung Typ Namensfilter auch bereitgestellt wird.
            </para>
          <para>
            Dieser Parameter entspricht, für die Groß-/Kleinschreibung beachtet genaue anwendungstypversion im Manifest Anwendung alle bereitgestellten oder Bereitstellung Anwendungstypen definiert.
            Beispielsweise entspricht Version "v1" nicht Version "1.0", da sie nur eine teilweise Übereinstimmung ist.
            Um alle anwendungstypversionen des Namens einer Anwendung anfordern, legen Sie diesen Wert nicht.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
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
          <para>Ermittelt oder definiert das Fortsetzungstoken, das zum Abrufen der nächsten Seite verwendet werden kann.</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Wird standardmäßig auf Null, was die Seite eine Abfrageergebnisse zurückgibt.
            </para>
          <para>
            Wenn zu viele Ergebnisse den Filter berücksichtigt, können sie eine Nachricht nicht ausreicht.
            Paging wird verwendet, um dies zu berücksichtigen und teilen Sie die Auflistung der <see cref="T:System.Fabric.Query.ApplicationType" />s in getrennte Seiten.
            Das Fortsetzungstoken wird verwendet, um wissen, an die vorherige Seite unterbrochen Durchführung der "significance" nur für die Abfrage selbst.
            Dieser Wert Ausführung dieser Abfrage generiert werden soll, und übergeben werden kann, in der nächsten abfrageanforderung, um auf den nachfolgenden Seiten zu erhalten.
            Ein fortsetzungstokenwert ungleich Null wird als Teil des Resultsets zurückgegeben werden, nur, wenn eine nachfolgende Seite vorhanden ist.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
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
          <para>Ruft ab oder legt fest, ob das Abfrageergebnis Anwendungsparameter ausgeschlossen.</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Der Standardwert ist "false".
            </para>
          <para>
            Eine Einstellung auf "true" bewirkt, dass die <see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" /> leer.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
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
            Ruft ab oder legt die maximale Anzahl von <see cref="T:System.Fabric.Query.ApplicationType" />s, die pro Seite zurückgegeben werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Der Standardwert ist der maximale Wert vom Typ long.
            </para>
          <para>Dadurch wird nur die obere Grenze für die Anzahl von Anwendungstypen zurückgegeben wird, nicht auf ein Minimum definiert.
            Beispielsweise, wenn die Seite höchstens 1000 zurückgegeben passt Elemente nach der maximalen Größe des Nachrichtenempfangs in der Konfiguration definiert und der Wert von "maxresults" auf 2000 festgelegt ist, und klicken Sie dann nur 1000 Ergebnisse zurückgegeben werden, auch wenn 2000 Anwendungstypen Beschreibung der Abfrage übereinstimmen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pagedApplicationTypeQueryDescription.ToString " />
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
            Überschreibt ToString()-Methode, um alle Inhalte der Beschreibung der Abfrage zu drucken.
            </summary>
        <returns>
            Gibt eine Zeichenfolge, enthält alle Eigenschaften der Beschreibung der Abfrage zurück.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>