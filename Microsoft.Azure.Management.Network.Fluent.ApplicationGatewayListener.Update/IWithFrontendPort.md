<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Listeners Front-End-Anwendung Gateway aktualisieren an den Front-End-Port zum Zuordnen des Listeners mit dem zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">eine Portnummer an.</param>
        <summary>
            Ermöglicht die Überwachung für die Anzahl der angegebene Front-End-Port gelauscht.
            Wenn Sie ein Front-End-Port für diese Portnummer noch nicht vorhanden ist, wird ein neues mit einem automatisch generierten Namen erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontendPort.WithFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort name" />
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
        <param name="name">Der Name des einen vorhandenen Front-End-Port.</param>
        <summary>
            Ermöglicht die Überwachung für den angegebenen vorhandenen Front-End-Port lauschen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>