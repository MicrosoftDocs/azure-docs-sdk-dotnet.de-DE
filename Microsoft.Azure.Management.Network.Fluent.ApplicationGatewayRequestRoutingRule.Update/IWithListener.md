<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regel Update taktmonitoren Geben Sie einen vorhandenen Listener um die Weiterleitungsregel mit zuzuordnen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener.FromListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithListener.FromListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name eines Listeners zu verweisen.</param>
        <summary>
            Ordnet die Weiterleitungsregel Anfrage einen vorhandenen Front-End-Listener.
            Beachten Sie, ein bestimmter Listener von nicht mehr als eine Anforderung Routingregel zu einem Zeitpunkt verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>