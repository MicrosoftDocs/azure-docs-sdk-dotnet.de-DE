<Type Name="IWithDestinationPort" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort">
  <TypeSignature Language="C#" Value="public interface IWithDestinationPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationPort" />
  <TypeSignature Language="F#" Value="type IWithDestinationPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der Beschreibung der Netzwerk-Regel ermöglicht die Ziel-Ports angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToAnyPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToAnyPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToAnyPort" />
      <MemberSignature Language="VB.NET" Value="Public Function ToAnyPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToAnyPort : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToAnyPort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Macht diese Regel auf einen beliebigen Port angewendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="ToPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToPort (port As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port">Die Zielportnummer an.</param>
        <summary>
            Gibt den Zielport für den diese Regel gilt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="ToPortRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPortRange (int from, int to);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate ToPortRange(int32 from, int32 to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithDestinationPort.ToPortRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToPortRange (from As Integer, to As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToPortRange : int * int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithDestinationPort.ToPortRange (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Int32" />
        <Parameter Name="to" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="from">Die erste Portnummer.</param>
        <param name="to">Die letzte Portnummer.</param>
        <summary>
            Gibt die Ziel-Portbereich für den diese Regel gilt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>