<Type Name="DesiredPropertyUpdateCallback" FullName="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task DesiredPropertyUpdateCallback(TwinCollection desiredProperties, object userContext);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DesiredPropertyUpdateCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function DesiredPropertyUpdateCallback(desiredProperties As TwinCollection, userContext As Object) As Task " />
  <TypeSignature Language="F#" Value="type DesiredPropertyUpdateCallback = delegate of TwinCollection * obj -&gt; Task" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="desiredProperties" Type="Microsoft.Azure.Devices.Shared.TwinCollection" />
    <Parameter Name="userContext" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="desiredProperties">Eigenschaften, die im Update enthalten waren, die vom Dienst empfangen wurde</param>
    <param name="userContext">Context-Objekt übergeben, wenn der Rückruf registriert wurde</param>
    <summary>
            Der Delegat für die gewünschte Eigenschaft Update Rückrufe.  Dies wird jedes Mal, wenn wir einen PATCH vom Dienst empfangen aufgerufen.
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>