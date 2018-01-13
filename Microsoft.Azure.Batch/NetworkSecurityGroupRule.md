<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Batch.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class&#xA;    interface ITransportObjectProvider&lt;NetworkSecurityGroupRule&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Netzwerksicherheits-Gruppenregel an einen Endpunkt eingehenden anwenden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.NetworkSecurityGroupRule : int * Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Batch.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Batch.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority">Die Priorität für diese Regel.</param>
        <param name="access">Die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</param>
        <param name="sourceAddressPrefix">Der Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Aktion ab, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Priorität für diese Regel an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Prioritäten in einem Pool müssen eindeutig sein und werden in der Reihenfolge ihrer Priorität ausgewertet. Je niedriger die Nummer ist, desto höher ist die Priorität. Beispielsweise können Regeln mit den Ordnungszahlen von 150, 250 und 350 angegeben werden. Die Regel mit der fortlaufenden Nummer der 150 Vorrang vor der Regel mit einer Bestellung von 250. Zulässige Prioritäten sind 150-3500 an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Gültige Werte sind eine einzelne IP-Adresse (d. h. 10.10.10.10), die IP-Subnetz (d. h. 192.168.1.0/24), die Standard-Tag oder * (für alle Adressen).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>