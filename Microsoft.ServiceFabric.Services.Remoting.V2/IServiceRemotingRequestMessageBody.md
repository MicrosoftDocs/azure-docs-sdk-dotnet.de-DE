<Type Name="IServiceRemotingRequestMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestMessageBody" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestMessageBody = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Schnittstelle, die implementiert werden muss, um Nachrichtentext anfordern für Remoteanforderungen bereitzustellen.
            Dieses Objekt enthält alles, was die Parameter Remoting-Methode hat.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetParameter">
      <MemberSignature Language="C#" Value="public object GetParameter (int position, string parameName, Type paramType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetParameter(int32 position, string parameName, class System.Type paramType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody.GetParameter(System.Int32,System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetParameter (position As Integer, parameName As String, paramType As Type) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetParameter : int * string * Type -&gt; obj" Usage="iServiceRemotingRequestMessageBody.GetParameter (position, parameName, paramType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int32" />
        <Parameter Name="parameName" Type="System.String" />
        <Parameter Name="paramType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="position">Die Position des Parameters in Remoting-Methode.</param>
        <param name="parameName">Name des Parameters in der Remoting-Methode</param>
        <param name="paramType">Parametertyp</param>
        <summary>
            Dies wird von Anforderung Text abrufen-Parameter verwendet, vor der Verteilung zur Dienstmethode-Remoting erfolgt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetParameter">
      <MemberSignature Language="C#" Value="public void SetParameter (int position, string parameName, object parameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetParameter(int32 position, string parameName, object parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody.SetParameter(System.Int32,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetParameter (position As Integer, parameName As String, parameter As Object)" />
      <MemberSignature Language="F#" Value="abstract member SetParameter : int * string * obj -&gt; unit" Usage="iServiceRemotingRequestMessageBody.SetParameter (position, parameName, parameter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="position" Type="System.Int32" />
        <Parameter Name="parameName" Type="System.String" />
        <Parameter Name="parameter" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="position">Die Position des Parameters in Remoting-Methode.</param>
        <param name="parameName">Name des Parameters in der Remoting-Methode</param>
        <param name="parameter">Parameterwert</param>
        <summary>
            Diese Api wird aufgerufen, um Remoting-Methodenparameter festzulegen, bevor Sie die Anforderung serialisieren/verteilt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>