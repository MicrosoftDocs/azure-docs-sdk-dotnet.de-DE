<Type Name="RuleDescription" FullName="Microsoft.Azure.ServiceBus.RuleDescription">
  <TypeSignature Language="C#" Value="public sealed class RuleDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RuleDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RuleDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleDescription" />
  <TypeSignature Language="F#" Value="type RuleDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Beschreibung des eine Regel darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" />-Klasse mit Standardwerten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : Microsoft.Azure.ServiceBus.Filter -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription filter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="filter">Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> Klasse mit dem angegebenen Filterausdruck.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : string -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" />-Klasse mit dem angegebenen Namen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : string * Microsoft.Azure.ServiceBus.Filter -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription (name, filter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="filter">Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> Klasse mit dem angegebenen Namen und die Filter-Ausdruck.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.RuleAction Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.RuleAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As RuleAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.ServiceBus.RuleAction with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.RuleAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion ausführen, wenn die Nachricht der Filterausdruck erfüllt.
            </summary>
        <value>Die Aktion ausführen, wenn die Nachricht der Filterausdruck erfüllt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultRuleName : string" Usage="Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />
      <MemberType>Field</MemberType>
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
            Ruft den Namen der Standardregel für das Abonnement ab.
            </summary>
        <remarks>
            Wenn ein neues Abonnement erstellt wird, wird immer eine Standardregel hinzugefügt.
            Die Standardregel ein <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Dadurch werden alle Nachrichten im Thema zum Abonnement zu erreichen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Filter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.Filter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As Filter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.Azure.ServiceBus.Filter with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Filter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Filterausdruck verwendet, um Nachrichten zu vergleichen.
            </summary>
        <value>Der Filterausdruck verwendet, um Nachrichten zu vergleichen.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Null (Nothing in Visual Basic) zugewiesen.</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Name" />
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
            Ruft ab oder legt den Namen der Regel.
            </summary>
        <value>Gibt eine <see cref="T:System.String" /> , die den Namen der Regel.</value>
        <remarks>Maximal zulässige Länge von Regelname ist 50 Zeichen.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>