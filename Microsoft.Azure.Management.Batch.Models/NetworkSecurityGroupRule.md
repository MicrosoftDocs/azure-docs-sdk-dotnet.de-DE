<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NetworkSecurityGroupRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule : int * Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority">Die Priorität für diese Regel.</param>
        <param name="access">Die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</param>
        <param name="sourceAddressPrefix">Der Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.</param>
        <summary>
            Initialisiert eine neue Instanz der NetworkSecurityGroupRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Zulassen", "Ablehnen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Priorität für diese Regel fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Prioritäten in einem Pool müssen eindeutig sein und werden in der Reihenfolge ihrer Priorität ausgewertet. Je niedriger die Nummer ist, desto höher ist die Priorität. Beispielsweise können Regeln mit den Ordnungszahlen von 150, 250 und 350 angegeben werden. Die Regel mit der fortlaufenden Nummer der 150 Vorrang vor der Regel mit einer Bestellung von 250. Zulässige Prioritäten sind 150-3500 an. Wenn alle reservierten oder doppelte Werte, dass die Anforderung mit HTTP-Statuscode 400 schlägt fehl bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Adresspräfix der Quelle oder Tag, das für die Regel abgeglichen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Gültige Werte sind eine einzelne IP-Adresse (d. h. 10.10.10.10), die IP-Subnetz (d. h. 192.168.1.0/24), die Standard-Tag oder * (für alle Adressen).  Wenn ein anderer werden die Werte bereitgestellt, die Anforderung mit HTTP-Statuscode 400 ein Fehler auftritt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSecurityGroupRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>