<Type Name="ApplicationQueryDescription" FullName="System.Fabric.Description.ApplicationQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationQueryDescription = class" />
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
      <para>Stellt abfrageeingaben verwendeten <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationQueryDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationDefinitionKindFilter As ApplicationDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationDefinitionKindFilter : System.Fabric.Description.ApplicationDefinitionKindFilter with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder Festlegen der definitionsart verwendet, um die Anwendungen zu filtern, die zurückgegeben werden.
            </para>
        </summary>
        <value>
          <para>Die definitionsart verwendet, um die Anwendungen zu filtern.</para>
        </value>
        <remarks>
          <para>Höchstens eine der ApplicationNameFilter, ApplicationTypeNameFilter oder ApplicationDefinitionKindFilter kann angegeben werden.</para>
          <para>Wenn keine Filter angegeben werden, werden alle Anwendungen zurückgegeben, die eine Seite passt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den URI-Namen der Anwendung bei der Abfrage.</para>
        </summary>
        <value>
          <para>Der Name der URI der Anwendung zum Abfragen.</para>
        </value>
        <remarks>
          <para>Höchstens eine der ApplicationNameFilter, ApplicationTypeNameFilter oder ApplicationDefinitionKindFilter kann angegeben werden.</para>
          <para>Wenn keine Filter angegeben werden, werden alle Anwendungen, die Anpassung an eine Seitengröße zurückgegeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
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
          <para>Ruft ab oder legt der Name des Anwendungstyps verwendet, um die Anwendungen bei der Abfrage zu filtern.
            Anwendungen, die von diesem Anwendungstyp sind, werden zurückgegeben.</para>
        </summary>
        <value>
          <para>Der Name des Anwendungstyps verwendet, um die Anwendungen bei der Abfrage zu filtern.</para>
        </value>
        <remarks>
          <para>Höchstens eine der ApplicationNameFilter, ApplicationTypeNameFilter oder ApplicationDefinitionKindFilter kann angegeben werden.</para>
          <para>Wenn keine Filter angegeben werden, werden alle Anwendungen, die Anpassung an eine Seitengröße zurückgegeben.</para>
          <para>Dieser Filter ist Groß-/Kleinschreibung beachtet.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
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
          <para>Ruft ab oder legt das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Das Token, das zum Abrufen der nächsten Seite von Abfragen verwendet werden kann.</para>
        </value>
        <remarks>
          <para>ContinuationToken wird von einer vorherigen Abfrage empfangen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
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
          <para>Ruft ab oder legt das Flag, die angibt, ob die Anwendungsparameter vom Ergebnis ausgeschlossen werden.</para>
        </summary>
        <value>
          <para>Flag, die angibt, ob die Anwendungsparameter vom Ergebnis ausgeschlossen werden.</para>
        </value>
        <remarks>
          <para>Dieses Flag kann festgelegt werden, auf "true", um den ergebnisumfang zu beschränken, wenn Parameter riesige sind.
            Der Standardwert ist „false“.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>