<Type Name="IWithIdleTimeoutInMinutes" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeoutInMinutes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase des Lastenausgleichs Regel Update festlegen, dass das Verbindungstimeout für Verbindungen im Leerlauf zu ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate" Usage="iWithIdleTimeoutInMinutes.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes">Die gewünschte Anzahl von Minuten.</param>
        <summary>
            Gibt die Anzahl von Minuten, bevor eine Verbindung im Leerlauf geschlossen wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>