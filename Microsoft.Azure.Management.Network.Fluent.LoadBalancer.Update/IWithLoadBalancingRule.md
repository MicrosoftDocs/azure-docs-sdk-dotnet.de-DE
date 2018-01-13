<Type Name="IWithLoadBalancingRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancingRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancingRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancingRule" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancingRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe des Load Balancers aktualisieren, sodass hinzufügen, entfernen oder Ändern von Load balancer-Regeln.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.DefineLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineLoadBalancingRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithLoadBalancingRule.DefineLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des der lastenausgleichsregel.</param>
        <summary>
            Beginn der Definition einer neuen lastenausgleichsregel zum Lastenausgleich hinzufügen.
            Die Definition muss mit einem Aufruf von LoadBalancerTcpProbe.DefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Stufe der neue Regeldefinition für den Lastenausgleich.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.UpdateLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate" Usage="iWithLoadBalancingRule.UpdateLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der lastenausgleichsregel zu aktualisieren.</param>
        <summary>
            Startet die Beschreibung des ein Update für eine vorhandene lastenausgleichsregel für dieses Lastenausgleichsmodul.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des Load balancing Regel Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.WithoutLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithLoadBalancingRule.WithoutLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des zu entfernenden Regel Lastenausgleich.</param>
        <summary>
            Entfernt die angegebene lastenausgleichsregel aus dem Lastenausgleich, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>