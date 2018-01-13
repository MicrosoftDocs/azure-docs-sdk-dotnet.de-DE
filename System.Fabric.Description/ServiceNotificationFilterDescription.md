<Type Name="ServiceNotificationFilterDescription" FullName="System.Fabric.Description.ServiceNotificationFilterDescription">
  <TypeSignature Language="C#" Value="public class ServiceNotificationFilterDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceNotificationFilterDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceNotificationFilterDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNotificationFilterDescription" />
  <TypeSignature Language="F#" Value="type ServiceNotificationFilterDescription = class" />
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
      <para>Stellt eine Klasse, die verwendet wird, um einen Filter für die Übermittlung der Benachrichtigung Service, beschreiben registriert über <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription (Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor(System.Uri,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As Uri, matchNamePrefix As Boolean, matchPrimaryChangeOnly As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceNotificationFilterDescription : Uri * bool * bool -&gt; System.Fabric.Description.ServiceNotificationFilterDescription" Usage="new System.Fabric.Description.ServiceNotificationFilterDescription (name, matchNamePrefix, matchPrimaryChangeOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="matchNamePrefix" Type="System.Boolean" />
        <Parameter Name="matchPrimaryChangeOnly" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name, für welchen Dienst Benachrichtigungen übermittelt werden soll.</para>
        </param>
        <param name="matchNamePrefix">
          <para>Flag, die angibt, ob alle Benachrichtigungen service für die Namen ein Präfix ist wird übermittelt.</para>
        </param>
        <param name="matchPrimaryChangeOnly">
          <para>Flag, die angibt, ob entsprechend der Anzahl der Übermittlung der Benachrichtigung durch Herausfiltern von Benachrichtigungen, die in denen das primäre Replikat-Endpunkts nicht geändert hat. Dieses Flag hat keine Auswirkungen für zustandslose Dienste.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchNamePrefix">
      <MemberSignature Language="C#" Value="public bool MatchNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchNamePrefix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchNamePrefix As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchNamePrefix : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
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
          <para>Ruft einen Wert, der angibt, ob alle dienstbenachrichtigungen, die für die Namen ein Präfix ist übermittelt werden soll.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn alle Service-Benachrichtigung für den Namen ein Präfix ist geliefert wurde, andernfalls wird <languageKeyword>"false"</languageKeyword>. Die Standardeinstellung ist <languageKeyword>false</languageKeyword>.</para>
        </value>
        <remarks>
            Der Präfix-Vergleich tritt auf, als Dienstnamen ein zeichenfolgenpräfix, anstatt eine URI-Segment Präfix Übereinstimmung verglichen. Ein Filter mit dem Namen "Fabric: / Abc" wird als Präfix Übereinstimmung Dienste mit dem Namen "Fabric: / Abc" und "Fabric: / Abc/Def", jedoch nicht um einen Dienst mit dem Namen "Fabric: / Abc_def".
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchPrimaryChangeOnly">
      <MemberSignature Language="C#" Value="public bool MatchPrimaryChangeOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchPrimaryChangeOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchPrimaryChangeOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchPrimaryChangeOnly : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
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
          <para>Ruft einen Wert, der angibt, ob die Anzahl der Übermittlung der Benachrichtigung abgeglichen, indem Herausfiltern von Benachrichtigungen, die in denen das primäre Replikat-Endpunkts nicht geändert hat. Dieses Flag hat keine Auswirkungen für zustandslose Dienste.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> , wenn die Filterung mit primären Änderung, andernfalls übereinstimmt <languageKeyword>"false"</languageKeyword>. Die Standardeinstellung ist <languageKeyword>false</languageKeyword>.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Uri Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Uri" />
      <MemberSignature Language="F#" Value="member this.Name : Uri with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
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
          <para>Ruft den Namen für die, den Service Benachrichtigungen übermittelt werden soll. Der Name muss im Fabric: Schema. Der Stammname ("Fabric:") ist zulässig.</para>
        </summary>
        <value>
          <para>Der Name, für welchen Dienst Benachrichtigungen übermittelt werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>