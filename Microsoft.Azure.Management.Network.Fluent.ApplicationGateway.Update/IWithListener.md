<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase von einer Anwendung Gateway Update ermöglicht Front-End-Listener ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.DefineListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineListener (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithListener.DefineListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein eindeutiger Name für den Listener.</param>
        <summary>
            Beginn der Definition einer neuen Anwendung Gateway Listener an das Gateway angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition des Listeners.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.UpdateListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithListener.UpdateListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name eines vorhanden Listeners aktualisieren.</param>
        <summary>
            Startet das Update eines Listeners.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Definition oder Null, wenn der angeforderte Listener nicht vorhanden ist.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.WithoutListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithListener.WithoutListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Listeners zu entfernen.</param>
        <summary>
            Entfernt einen Front-End-Listener aus das Anwendungsgateway.
            Beachten Sie, dass das Entfernen eines Listeners verwiesen wird, indem Sie andere Einstellungen das Anwendungsgateway umgebrochen werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>